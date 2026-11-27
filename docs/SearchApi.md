# unipile.SearchApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_search_parameters**](SearchApi.md#get_search_parameters) | **GET** /v2/{account_id}/search/parameters | List Search Parameters
[**perform_pages_search**](SearchApi.md#perform_pages_search) | **POST** /v2/{account_id}/search/pages | Perform Pages Search
[**perform_people_search**](SearchApi.md#perform_people_search) | **POST** /v2/{account_id}/search/people | Perform People Search
[**perform_posts_search**](SearchApi.md#perform_posts_search) | **POST** /v2/{account_id}/search/posts | Perform Posts Search


# **get_search_parameters**
> SearchParametersList get_search_parameters(type, account_id, keywords=keywords, limit=limit)

List Search Parameters

Returns the cities, schools, companies or event categories whose name matches the given keywords, with the ID to give to the matching filter of the people, pages, posts and events searches.
      LIMITATIONS: Available on Facebook. Cities, schools and companies are Facebook's suggestions, 10 at most: give a full name (`HEC Paris` rather than `HEC`). A school or company can have several pages (campuses, duplicates), and a filter only finds the people who chose that page. Event categories are a fixed list, named in the account's language: all of them without `keywords`, or those whose name contains it.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.search_parameters_list import SearchParametersList
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.SearchApi(api_client)
    type = 'type_example' # str | The filter to look values up for.   - `location` cities, for the `location` filters of the searches.   - `school` schools, for the `school` filter of the people search.   - `company` companies, for the `company` filter of the people search.   - `event_category` event categories, for the `category` filter of the events search.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    keywords = 'keywords_example' # str | The name, or part of the name, to look for. Required, except for `event_category`: without it, every category is returned. (optional)
    limit = 10 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 10)

    try:
        # List Search Parameters
        api_response = api_instance.get_search_parameters(type, account_id, keywords=keywords, limit=limit)
        print("The response of SearchApi->get_search_parameters:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SearchApi->get_search_parameters: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type** | **str**| The filter to look values up for.   - &#x60;location&#x60; cities, for the &#x60;location&#x60; filters of the searches.   - &#x60;school&#x60; schools, for the &#x60;school&#x60; filter of the people search.   - &#x60;company&#x60; companies, for the &#x60;company&#x60; filter of the people search.   - &#x60;event_category&#x60; event categories, for the &#x60;category&#x60; filter of the events search. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **keywords** | **str**| The name, or part of the name, to look for. Required, except for &#x60;event_category&#x60;: without it, every category is returned. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 10]

### Return type

[**SearchParametersList**](SearchParametersList.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The values found for the filter. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_pages_search**
> PagesSearchResults perform_pages_search(account_id, perform_pages_search_request, cursor=cursor, limit=limit)

Perform Pages Search

Returns the pages (businesses, brands, public figures...) matching the given keywords and filters, as users of type `organization` described by what the search shows about them (category, address, audience...). Send the same body with `cursor` to get the next pages.
      LIMITATIONS: Available on Facebook. On Facebook, the page size is set by Facebook whatever the `limit` (usually 10 to 20 results), a list filter takes one ID, and an ID Facebook does not know is ignored. LinkedIn company searches have their own route (`/linkedin/search/companies`).
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.pages_search_results import PagesSearchResults
from unipile.models.perform_pages_search_request import PerformPagesSearchRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.SearchApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    perform_pages_search_request = unipile.PerformPagesSearchRequest() # PerformPagesSearchRequest | The criteria of the search.
    cursor = 'cursor_example' # str | A cursor used for pagination. Use `next_cursor` given by the previous page of the list. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # Perform Pages Search
        api_response = api_instance.perform_pages_search(account_id, perform_pages_search_request, cursor=cursor, limit=limit)
        print("The response of SearchApi->perform_pages_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SearchApi->perform_pages_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **perform_pages_search_request** | [**PerformPagesSearchRequest**](PerformPagesSearchRequest.md)| The criteria of the search. | 
 **cursor** | **str**| A cursor used for pagination. Use &#x60;next_cursor&#x60; given by the previous page of the list. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]

### Return type

[**PagesSearchResults**](PagesSearchResults.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The pages found, as users of type &#x60;organization&#x60;. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_people_search**
> PeopleSearchResults perform_people_search(account_id, perform_people_search_request, cursor=cursor, limit=limit)

Perform People Search

Returns the people matching the given keywords and filters, as users described by what the search shows about them (where they live, study or work...). Send the same body with `cursor` to get the next pages.
      LIMITATIONS: Available on Facebook. On Facebook, the page size is set by Facebook whatever the `limit` (usually 10 to 20 results), a list filter takes one ID, and an ID Facebook does not know is ignored. `network_distance` takes one degree, `[1]` (friends) or `[2]` (friends of friends), and cannot be combined with `connections_of`. LinkedIn people searches have their own routes (`/linkedin/search/people`).
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.people_search_results import PeopleSearchResults
from unipile.models.perform_people_search_request import PerformPeopleSearchRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.SearchApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    perform_people_search_request = unipile.PerformPeopleSearchRequest() # PerformPeopleSearchRequest | The criteria of the search.
    cursor = 'cursor_example' # str | A cursor used for pagination. Use `next_cursor` given by the previous page of the list. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # Perform People Search
        api_response = api_instance.perform_people_search(account_id, perform_people_search_request, cursor=cursor, limit=limit)
        print("The response of SearchApi->perform_people_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SearchApi->perform_people_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **perform_people_search_request** | [**PerformPeopleSearchRequest**](PerformPeopleSearchRequest.md)| The criteria of the search. | 
 **cursor** | **str**| A cursor used for pagination. Use &#x60;next_cursor&#x60; given by the previous page of the list. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]

### Return type

[**PeopleSearchResults**](PeopleSearchResults.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The people found, as users. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_posts_search**
> GetPostsList200Response perform_posts_search(account_id, perform_posts_search_request, cursor=cursor, limit=limit)

Perform Posts Search

Returns the posts matching the given keywords and filters that the account owner can see. Send the same body with `cursor` to get the next pages.
      LIMITATIONS: Available on Facebook. On Facebook, the page size is set by Facebook whatever the `limit` (usually 10 to 20 results), a list filter takes one ID, and an ID Facebook does not know is ignored. `start_date` and `end_date` are days of the account's time zone, from 2004 on. `posted_by` takes one option at a time (`me`, `my_groups_and_pages`, `public`, or one ID in `member`, `company` or `group`), and `seen` only `true`. LinkedIn post searches have their own route (`/linkedin/search/posts`).
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_posts_list200_response import GetPostsList200Response
from unipile.models.perform_posts_search_request import PerformPostsSearchRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.SearchApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    perform_posts_search_request = unipile.PerformPostsSearchRequest() # PerformPostsSearchRequest | The criteria of the search.
    cursor = 'cursor_example' # str | A cursor used for pagination. Use `next_cursor` given by the previous page of the list. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # Perform Posts Search
        api_response = api_instance.perform_posts_search(account_id, perform_posts_search_request, cursor=cursor, limit=limit)
        print("The response of SearchApi->perform_posts_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling SearchApi->perform_posts_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **perform_posts_search_request** | [**PerformPostsSearchRequest**](PerformPostsSearchRequest.md)| The criteria of the search. | 
 **cursor** | **str**| A cursor used for pagination. Use &#x60;next_cursor&#x60; given by the previous page of the list. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]

### Return type

[**GetPostsList200Response**](GetPostsList200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

