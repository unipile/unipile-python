# unipile.GroupsApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**add_group_member**](GroupsApi.md#add_group_member) | **POST** /v2/{account_id}/groups/{group_id}/members | Add a Member to a Group
[**create_group**](GroupsApi.md#create_group) | **POST** /v2/{account_id}/groups | Create a Group
[**create_group_post**](GroupsApi.md#create_group_post) | **POST** /v2/{account_id}/groups/{group_id}/posts | Create a Post in a Group
[**get_group**](GroupsApi.md#get_group) | **GET** /v2/{account_id}/groups/{group_id} | Get a Group
[**get_group_events_list**](GroupsApi.md#get_group_events_list) | **GET** /v2/{account_id}/groups/{group_id}/events | List all Group&#39;s Events
[**get_group_members_list**](GroupsApi.md#get_group_members_list) | **GET** /v2/{account_id}/groups/{group_id}/members | List all Group&#39;s Members
[**get_group_posts_list**](GroupsApi.md#get_group_posts_list) | **GET** /v2/{account_id}/groups/{group_id}/posts | List all Group&#39;s Posts
[**join_group**](GroupsApi.md#join_group) | **POST** /v2/{account_id}/groups/{group_id}/join | Join a Group
[**perform_groups_search**](GroupsApi.md#perform_groups_search) | **POST** /v2/{account_id}/search/groups | Perform Groups Search


# **add_group_member**
> AddGroupMember200Response add_group_member(group_id, account_id, add_group_member_request)

Add a Member to a Group

Adds a user to a social group the account owner administers, or invites them to it.
      LIMITATIONS: On Facebook and LinkedIn, the user must be a relation of the account owner (a friend on Facebook) and is invited: they join once they accept. On Facebook, a user already invited gets a 409. On LinkedIn, a refused invitation gets a 403 when the account cannot invite to the group, a 400 otherwise.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.add_group_member200_response import AddGroupMember200Response
from unipile.models.add_group_member_request import AddGroupMemberRequest
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
    api_instance = unipile.GroupsApi(api_client)
    group_id = 'group_id_example' # str | The ID of the social group. Use an ID returned by *Perform Groups Search*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    add_group_member_request = unipile.AddGroupMemberRequest() # AddGroupMemberRequest | The user to add to the group or community.

    try:
        # Add a Member to a Group
        api_response = api_instance.add_group_member(group_id, account_id, add_group_member_request)
        print("The response of GroupsApi->add_group_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling GroupsApi->add_group_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_id** | **str**| The ID of the social group. Use an ID returned by *Perform Groups Search*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **add_group_member_request** | [**AddGroupMemberRequest**](AddGroupMemberRequest.md)| The user to add to the group or community. | 

### Return type

[**AddGroupMember200Response**](AddGroupMember200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The request to add or invite the member was successful. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_group**
> PerformGroupsSearch200ResponseDataInner create_group(account_id, create_group_request)

Create a Group

Creates a social group administered by the account owner, private unless `is_public`, and returns it. Use the Messaging API to start a group conversation. If the full group is temporarily unavailable after creation, the response still includes its ID, name and the account owner's membership.
      LIMITATIONS: On Facebook, `description` is not supported (400). On LinkedIn, members can invite their relations and admins review new posts; a private group (the default) does not appear in LinkedIn's search, and only its members see its posts.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_group_request import CreateGroupRequest
from unipile.models.perform_groups_search200_response_data_inner import PerformGroupsSearch200ResponseDataInner
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
    api_instance = unipile.GroupsApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_group_request = unipile.CreateGroupRequest() # CreateGroupRequest | The social group to create.

    try:
        # Create a Group
        api_response = api_instance.create_group(account_id, create_group_request)
        print("The response of GroupsApi->create_group:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling GroupsApi->create_group: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_group_request** | [**CreateGroupRequest**](CreateGroupRequest.md)| The social group to create. | 

### Return type

[**PerformGroupsSearch200ResponseDataInner**](PerformGroupsSearch200ResponseDataInner.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | A social group with members, posts and, where available, events. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_group_post**
> Post2 create_group_post(group_id, account_id, create_group_post_request)

Create a Post in a Group

Publishes a new post in a social group the account owner is a member of. The post is visible to whoever can see the group's posts.
      LIMITATIONS: The post is published by the account owner: publishing as a company page is not supported. Available for Facebook and LinkedIn.
      <br/><br/>Multipart supported, refer to <a href="https://developer.unipile.com/v2.0/reference/api-usage#sending-files">Sending Files</a>.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_group_post_request import CreateGroupPostRequest
from unipile.models.post2 import Post2
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
    api_instance = unipile.GroupsApi(api_client)
    group_id = 'group_id_example' # str | The ID of the social group. Use an ID returned by *Perform Groups Search*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_group_post_request = unipile.CreateGroupPostRequest() # CreateGroupPostRequest | The post to publish in the social group.

    try:
        # Create a Post in a Group
        api_response = api_instance.create_group_post(group_id, account_id, create_group_post_request)
        print("The response of GroupsApi->create_group_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling GroupsApi->create_group_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_id** | **str**| The ID of the social group. Use an ID returned by *Perform Groups Search*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_group_post_request** | [**CreateGroupPostRequest**](CreateGroupPostRequest.md)| The post to publish in the social group. | 

### Return type

[**Post2**](Post2.md)

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

# **get_group**
> PerformGroupsSearch200ResponseDataInner get_group(group_id, account_id)

Get a Group

Returns the details of a social group, with the membership of the account owner in it.
      LIMITATIONS: On Facebook, `is_admin` is also true for moderators, the description is returned when the account can see it, and `public_picture_url` is only returned by *Perform Groups Search*.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_groups_search200_response_data_inner import PerformGroupsSearch200ResponseDataInner
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
    api_instance = unipile.GroupsApi(api_client)
    group_id = 'group_id_example' # str | The ID of the social group. Use an ID returned by *Perform Groups Search*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Group
        api_response = api_instance.get_group(group_id, account_id)
        print("The response of GroupsApi->get_group:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling GroupsApi->get_group: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_id** | **str**| The ID of the social group. Use an ID returned by *Perform Groups Search*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**PerformGroupsSearch200ResponseDataInner**](PerformGroupsSearch200ResponseDataInner.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | A social group with members, posts and, where available, events. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_group_events_list**
> PerformEventsSearch200Response get_group_events_list(group_id, account_id, cursor=cursor, limit=limit, period=period)

List all Group's Events

Returns the upcoming social events of a group. Use `period` to list past events. Set `period` on the first request only. For later pages, pass `next_cursor` as `cursor`. The cursor carries the selected period.
      LIMITATIONS: On Facebook, the list has no dates and places (use *Get an Event*). Not supported on LinkedIn, whose groups have no events.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_events_search200_response import PerformEventsSearch200Response
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
    api_instance = unipile.GroupsApi(api_client)
    group_id = 'group_id_example' # str | The ID of the social group. Use an ID returned by *Perform Groups Search*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    cursor = 'cursor_example' # str | A cursor used for pagination. Use `next_cursor` given by the previous page of the list. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)
    period = 'period_example' # str | Whether to list upcoming events (the default) or past events. Omit this field when sending a cursor. (optional)

    try:
        # List all Group's Events
        api_response = api_instance.get_group_events_list(group_id, account_id, cursor=cursor, limit=limit, period=period)
        print("The response of GroupsApi->get_group_events_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling GroupsApi->get_group_events_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_id** | **str**| The ID of the social group. Use an ID returned by *Perform Groups Search*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **cursor** | **str**| A cursor used for pagination. Use &#x60;next_cursor&#x60; given by the previous page of the list. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]
 **period** | **str**| Whether to list upcoming events (the default) or past events. Omit this field when sending a cursor. | [optional] 

### Return type

[**PerformEventsSearch200Response**](PerformEventsSearch200Response.md)

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

# **get_group_members_list**
> GetGroupMembersList200Response get_group_members_list(group_id, account_id, cursor=cursor, limit=limit)

List all Group's Members

Returns the members of a social group and indicates whether each member is an admin.
      LIMITATIONS: On Facebook, the newest members come first, up to 10 per page whatever the `limit`; `is_admin` also marks moderators and can take a few minutes to update. On LinkedIn, only members can list the members (403 otherwise); owners and managers are admins.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_group_members_list200_response import GetGroupMembersList200Response
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
    api_instance = unipile.GroupsApi(api_client)
    group_id = 'group_id_example' # str | The ID of the social group. Use an ID returned by *Perform Groups Search*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    cursor = 'cursor_example' # str | A cursor used for pagination. Use `next_cursor` given by the previous page of the list. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # List all Group's Members
        api_response = api_instance.get_group_members_list(group_id, account_id, cursor=cursor, limit=limit)
        print("The response of GroupsApi->get_group_members_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling GroupsApi->get_group_members_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_id** | **str**| The ID of the social group. Use an ID returned by *Perform Groups Search*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **cursor** | **str**| A cursor used for pagination. Use &#x60;next_cursor&#x60; given by the previous page of the list. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]

### Return type

[**GetGroupMembersList200Response**](GetGroupMembersList200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The members of the group or community. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_group_posts_list**
> GetPostsList200Response get_group_posts_list(group_id, account_id, offset=offset, cursor=cursor, limit=limit)

List all Group's Posts

Returns the posts published in a social group, newest first. Comment and react to them with the Posts methods.
      LIMITATIONS: The posts of a private group are returned to its members only: on Facebook, a non-member gets an empty list. On Facebook, each page holds a few posts whatever the `limit`: use `next_cursor` to get more. On LinkedIn, the comments of these posts are returned only once the account owner is a member. Available for Facebook and LinkedIn.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_posts_list200_response import GetPostsList200Response
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
    api_instance = unipile.GroupsApi(api_client)
    group_id = 'group_id_example' # str | The ID of the social group. Use an ID returned by *Perform Groups Search*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 56 # int | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # List all Group's Posts
        api_response = api_instance.get_group_posts_list(group_id, account_id, offset=offset, cursor=cursor, limit=limit)
        print("The response of GroupsApi->get_group_posts_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling GroupsApi->get_group_posts_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_id** | **str**| The ID of the social group. Use an ID returned by *Perform Groups Search*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **int**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]

### Return type

[**GetPostsList200Response**](GetPostsList200Response.md)

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

# **join_group**
> JoinGroup200Response join_group(group_id, account_id)

Join a Group

Joins the specified social group. When the group approves its members, a request to join is sent and the membership stays `pending` until it is approved.
      LIMITATIONS: On LinkedIn, the comments of a group's posts are visible to its members only.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.join_group200_response import JoinGroup200Response
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
    api_instance = unipile.GroupsApi(api_client)
    group_id = 'group_id_example' # str | The ID of the social group. Use an ID returned by *Perform Groups Search*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Join a Group
        api_response = api_instance.join_group(group_id, account_id)
        print("The response of GroupsApi->join_group:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling GroupsApi->join_group: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_id** | **str**| The ID of the social group. Use an ID returned by *Perform Groups Search*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**JoinGroup200Response**](JoinGroup200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The result of the request to join the social group. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_groups_search**
> PerformGroupsSearch200Response perform_groups_search(account_id, perform_groups_search_request, cursor=cursor, limit=limit)

Perform Groups Search

Returns the social groups matching the given keywords that the account owner can see, with its membership in each of them. Send the same body with `cursor` to get the next pages.
      LIMITATIONS: On Facebook, `is_member` and `is_public` only accept `true`. On LinkedIn, groups are searched by keywords only (`is_member` and `is_public` get a 400), up to 1000 results. Facebook and LinkedIn may return fewer results than `limit` per page: follow `next_cursor`.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_groups_search200_response import PerformGroupsSearch200Response
from unipile.models.perform_groups_search_request import PerformGroupsSearchRequest
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
    api_instance = unipile.GroupsApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    perform_groups_search_request = unipile.PerformGroupsSearchRequest() # PerformGroupsSearchRequest | The criteria of the search.
    cursor = 'cursor_example' # str | A cursor used for pagination. Use `next_cursor` given by the previous page of the list. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # Perform Groups Search
        api_response = api_instance.perform_groups_search(account_id, perform_groups_search_request, cursor=cursor, limit=limit)
        print("The response of GroupsApi->perform_groups_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling GroupsApi->perform_groups_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **perform_groups_search_request** | [**PerformGroupsSearchRequest**](PerformGroupsSearchRequest.md)| The criteria of the search. | 
 **cursor** | **str**| A cursor used for pagination. Use &#x60;next_cursor&#x60; given by the previous page of the list. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]

### Return type

[**PerformGroupsSearch200Response**](PerformGroupsSearch200Response.md)

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

