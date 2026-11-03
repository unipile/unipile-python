# unipile.OutlookApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_email_category**](OutlookApi.md#create_email_category) | **POST** /v2/{account_id}/outlook/email-categories | Create an email category
[**delete_email_category**](OutlookApi.md#delete_email_category) | **DELETE** /v2/{account_id}/outlook/email-categories/{category_name} | Delete an email category
[**get_category_emails_list**](OutlookApi.md#get_category_emails_list) | **GET** /v2/{account_id}/outlook/email-categories/{category_name}/emails | List category Emails
[**get_email_categories**](OutlookApi.md#get_email_categories) | **GET** /v2/{account_id}/outlook/email-categories | List email categories


# **create_email_category**
> GetEmailCategories200ResponseDataInner create_email_category(account_id, create_email_category_request)

Create an email category

Creates a new category in the account mailbox, which can then be assigned to emails through the `categories` field. A category name is unique within a mailbox: creating one with a name already in use returns a conflict.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_email_category_request import CreateEmailCategoryRequest
from unipile.models.get_email_categories200_response_data_inner import GetEmailCategories200ResponseDataInner
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
    api_instance = unipile.OutlookApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_email_category_request = unipile.CreateEmailCategoryRequest() # CreateEmailCategoryRequest | 

    try:
        # Create an email category
        api_response = api_instance.create_email_category(account_id, create_email_category_request)
        print("The response of OutlookApi->create_email_category:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling OutlookApi->create_email_category: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_email_category_request** | [**CreateEmailCategoryRequest**](CreateEmailCategoryRequest.md)|  | 

### Return type

[**GetEmailCategories200ResponseDataInner**](GetEmailCategories200ResponseDataInner.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_email_category**
> delete_email_category(category_name, account_id)

Delete an email category

Deletes the specific category from the account mailbox. Emails already carrying it keep the category name, which is no longer part of the mailbox list.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
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
    api_instance = unipile.OutlookApi(api_client)
    category_name = 'category_name_example' # str | Name of the Category to delete, as returned by the categories list endpoint.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Delete an email category
        api_instance.delete_email_category(category_name, account_id)
    except Exception as e:
        print("Exception when calling OutlookApi->delete_email_category: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **category_name** | **str**| Name of the Category to delete, as returned by the categories list endpoint. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

void (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_category_emails_list**
> GetEmailsList200Response get_category_emails_list(category_name, account_id, q=q, meta_only=meta_only, to=to, var_from=var_from, any_email=any_email, has_attachment=has_attachment, is_starred=is_starred, is_unread=is_unread, before=before, exclude_folder=exclude_folder, after=after, offset=offset, cursor=cursor, limit=limit)

List category Emails

Returns a list of emails carrying the specific category, across all the folders of the account mailbox. Emails are returned sorted by their `date`, with the most recent appearing first. Search mode applies when `q`, `from`, `to`, or `any_email` is set. Filter mode applies for browse-only queries (dates, folder scope, read/starred/attachment status).

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_emails_list200_response import GetEmailsList200Response
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
    api_instance = unipile.OutlookApi(api_client)
    category_name = 'category_name_example' # str | Name of the Category to retrieve emails from, as carried by the emails themselves and returned by the categories list endpoint. A category name is unique within a mailbox.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    q = 'q_example' # str | Full-text search in the email subject and body (case-insensitive, partial match). Activates search mode: results may be approximate and non-exhaustive (provider-dependent, ~1000 results on Outlook). Combine with `from`, `to`, or `any_email` to narrow by participant address. (optional)
    meta_only = False # bool | Speed up the response by only returning the email metadata. body and body_plain are empty strings, and attachments metadata is excluded. (optional) (default to False)
    to = 'to_example' # str | Return messages sent to the given email address. For Outlook, some messages matching this filter may be missing due to a provider limitation. Use `GET /threads/:thread_id` to retrieve a specific conversation. Activates search mode: results may be approximate and non-exhaustive (provider-dependent, ~1000 results on Outlook). (optional)
    var_from = 'var_from_example' # str | Return messages sent from the given email address. For Outlook, some messages matching this filter may be missing due to a provider limitation. Use `GET /threads/:thread_id` to retrieve a specific conversation. Activates search mode: results may be approximate and non-exhaustive (provider-dependent, ~1000 results on Outlook). (optional)
    any_email = 'any_email_example' # str | Return messages where at least one of the given comma-separated email addresses appears as a participant (from, to, cc, or bcc). For Outlook, some messages matching this filter may be missing due to a provider limitation. Use `GET /threads/:thread_id` to retrieve a specific conversation. Activates search mode: results may be approximate and non-exhaustive (provider-dependent, ~1000 results on Outlook). (optional)
    has_attachment = True # bool | Filter to only return emails with or without attachments. For Outlook with `meta_only=true`, this uses the provider attachment flag, which excludes inline attachments. (optional)
    is_starred = True # bool | Filter to only return starred or unstarred emails. (optional)
    is_unread = True # bool | Filter to only return unread or read emails. (optional)
    before = '2013-10-20T19:20:30+01:00' # datetime | Filter to only return emails sent before the given datetime (exclusive). Must use a supported date-time format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). (optional)
    exclude_folder = 'exclude_folder_example' # str | Filter to only return emails that are not in any of the folders specified in the comma-separated list of folder IDs. (optional)
    after = '2013-10-20T19:20:30+01:00' # datetime | Filter to only return emails sent after the given datetime (exclusive). Must use a supported date-time format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). (optional)
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)
    limit = 20 # float | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # List category Emails
        api_response = api_instance.get_category_emails_list(category_name, account_id, q=q, meta_only=meta_only, to=to, var_from=var_from, any_email=any_email, has_attachment=has_attachment, is_starred=is_starred, is_unread=is_unread, before=before, exclude_folder=exclude_folder, after=after, offset=offset, cursor=cursor, limit=limit)
        print("The response of OutlookApi->get_category_emails_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling OutlookApi->get_category_emails_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **category_name** | **str**| Name of the Category to retrieve emails from, as carried by the emails themselves and returned by the categories list endpoint. A category name is unique within a mailbox. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **q** | **str**| Full-text search in the email subject and body (case-insensitive, partial match). Activates search mode: results may be approximate and non-exhaustive (provider-dependent, ~1000 results on Outlook). Combine with &#x60;from&#x60;, &#x60;to&#x60;, or &#x60;any_email&#x60; to narrow by participant address. | [optional] 
 **meta_only** | **bool**| Speed up the response by only returning the email metadata. body and body_plain are empty strings, and attachments metadata is excluded. | [optional] [default to False]
 **to** | **str**| Return messages sent to the given email address. For Outlook, some messages matching this filter may be missing due to a provider limitation. Use &#x60;GET /threads/:thread_id&#x60; to retrieve a specific conversation. Activates search mode: results may be approximate and non-exhaustive (provider-dependent, ~1000 results on Outlook). | [optional] 
 **var_from** | **str**| Return messages sent from the given email address. For Outlook, some messages matching this filter may be missing due to a provider limitation. Use &#x60;GET /threads/:thread_id&#x60; to retrieve a specific conversation. Activates search mode: results may be approximate and non-exhaustive (provider-dependent, ~1000 results on Outlook). | [optional] 
 **any_email** | **str**| Return messages where at least one of the given comma-separated email addresses appears as a participant (from, to, cc, or bcc). For Outlook, some messages matching this filter may be missing due to a provider limitation. Use &#x60;GET /threads/:thread_id&#x60; to retrieve a specific conversation. Activates search mode: results may be approximate and non-exhaustive (provider-dependent, ~1000 results on Outlook). | [optional] 
 **has_attachment** | **bool**| Filter to only return emails with or without attachments. For Outlook with &#x60;meta_only&#x3D;true&#x60;, this uses the provider attachment flag, which excludes inline attachments. | [optional] 
 **is_starred** | **bool**| Filter to only return starred or unstarred emails. | [optional] 
 **is_unread** | **bool**| Filter to only return unread or read emails. | [optional] 
 **before** | **datetime**| Filter to only return emails sent before the given datetime (exclusive). Must use a supported date-time format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). | [optional] 
 **exclude_folder** | **str**| Filter to only return emails that are not in any of the folders specified in the comma-separated list of folder IDs. | [optional] 
 **after** | **datetime**| Filter to only return emails sent after the given datetime (exclusive). Must use a supported date-time format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). | [optional] 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]

### Return type

[**GetEmailsList200Response**](GetEmailsList200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_email_categories**
> GetEmailCategories200Response get_email_categories(account_id)

List email categories

Returns the categories defined in the account mailbox, so you can discover the valid values to assign to an email through the `categories` field. Categories are a mailbox-wide list, independent from folders: assigning one does not move the email. Subscribe to the `email.update` webhook event to be notified when the categories of an email change.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_email_categories200_response import GetEmailCategories200Response
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
    api_instance = unipile.OutlookApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # List email categories
        api_response = api_instance.get_email_categories(account_id)
        print("The response of OutlookApi->get_email_categories:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling OutlookApi->get_email_categories: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetEmailCategories200Response**](GetEmailCategories200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

