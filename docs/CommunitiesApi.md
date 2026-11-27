# unipile.CommunitiesApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**accept_community_join_request**](CommunitiesApi.md#accept_community_join_request) | **POST** /v2/{account_id}/communities/{community_id}/join-requests/{request_id}/accept | Accept a Community&#39;s Join Request
[**add_community_chat**](CommunitiesApi.md#add_community_chat) | **POST** /v2/{account_id}/communities/{community_id}/chats | Add a Chat to a Community
[**add_community_member**](CommunitiesApi.md#add_community_member) | **POST** /v2/{account_id}/communities/{community_id}/members | Add a Member to a Community
[**cancel_community_join_request**](CommunitiesApi.md#cancel_community_join_request) | **POST** /v2/{account_id}/communities/{community_id}/join-requests/{request_id}/cancel | Refuse a Community&#39;s Join Request
[**create_community**](CommunitiesApi.md#create_community) | **POST** /v2/{account_id}/communities | Create a Community
[**get_community**](CommunitiesApi.md#get_community) | **GET** /v2/{account_id}/communities/{community_id} | Get a Community
[**get_community_chats_list**](CommunitiesApi.md#get_community_chats_list) | **GET** /v2/{account_id}/communities/{community_id}/chats | List all Community&#39;s Chats
[**get_community_invite_link**](CommunitiesApi.md#get_community_invite_link) | **GET** /v2/{account_id}/communities/{community_id}/invite-link | Get a Community&#39;s Invite Link
[**get_community_join_requests_list**](CommunitiesApi.md#get_community_join_requests_list) | **GET** /v2/{account_id}/communities/{community_id}/join-requests | List all Community&#39;s Join Requests
[**get_community_members_list**](CommunitiesApi.md#get_community_members_list) | **GET** /v2/{account_id}/communities/{community_id}/members | List all Community&#39;s Members
[**join_community**](CommunitiesApi.md#join_community) | **POST** /v2/{account_id}/communities/{community_id}/join | Join a Community
[**leave_community**](CommunitiesApi.md#leave_community) | **POST** /v2/{account_id}/communities/{community_id}/leave | Leave a Community
[**perform_communities_search**](CommunitiesApi.md#perform_communities_search) | **POST** /v2/{account_id}/search/communities | Perform Communities Search
[**remove_community_chat**](CommunitiesApi.md#remove_community_chat) | **DELETE** /v2/{account_id}/communities/{community_id}/chats/{chat_id} | Remove a Chat from a Community
[**remove_community_member**](CommunitiesApi.md#remove_community_member) | **DELETE** /v2/{account_id}/communities/{community_id}/members/{user_id} | Remove a Member from a Community
[**reset_community_invite_link**](CommunitiesApi.md#reset_community_invite_link) | **POST** /v2/{account_id}/communities/{community_id}/invite-link/reset | Reset a Community&#39;s Invite Link
[**update_community**](CommunitiesApi.md#update_community) | **PATCH** /v2/{account_id}/communities/{community_id} | Update a Community
[**update_community_member**](CommunitiesApi.md#update_community_member) | **PATCH** /v2/{account_id}/communities/{community_id}/members/{user_id} | Update a Member of a Community


# **accept_community_join_request**
> AcceptCommunityJoinRequest200Response accept_community_join_request(community_id, request_id, account_id)

Accept a Community's Join Request

Accepts a request to join a community the account owner administers. The requester becomes a member.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.accept_community_join_request200_response import AcceptCommunityJoinRequest200Response
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    request_id = 'request_id_example' # str | The ID of the request. Use an ID returned by *List all Community's Join Requests*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Accept a Community's Join Request
        api_response = api_instance.accept_community_join_request(community_id, request_id, account_id)
        print("The response of CommunitiesApi->accept_community_join_request:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->accept_community_join_request: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **request_id** | **str**| The ID of the request. Use an ID returned by *List all Community&#39;s Join Requests*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**AcceptCommunityJoinRequest200Response**](AcceptCommunityJoinRequest200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The request was accepted: the user is a member. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_community_chat**
> GetCommunityChatsList200ResponseDataInner add_community_chat(community_id, account_id, add_community_chat_request=add_community_chat_request)

Add a Chat to a Community

Links an existing group chat the account owner administers (`chat_id`), or creates a group chat in the community (`name`). Returns the chat with its Messaging API ID.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.add_community_chat_request import AddCommunityChatRequest
from unipile.models.get_community_chats_list200_response_data_inner import GetCommunityChatsList200ResponseDataInner
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    add_community_chat_request = unipile.AddCommunityChatRequest() # AddCommunityChatRequest | Link an existing group chat (`chat_id`), or create a group chat (`name`). (optional)

    try:
        # Add a Chat to a Community
        api_response = api_instance.add_community_chat(community_id, account_id, add_community_chat_request=add_community_chat_request)
        print("The response of CommunitiesApi->add_community_chat:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->add_community_chat: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **add_community_chat_request** | [**AddCommunityChatRequest**](AddCommunityChatRequest.md)| Link an existing group chat (&#x60;chat_id&#x60;), or create a group chat (&#x60;name&#x60;). | [optional] 

### Return type

[**GetCommunityChatsList200ResponseDataInner**](GetCommunityChatsList200ResponseDataInner.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Summary of a group chat linked to a community. Use its &#x60;id&#x60; as &#x60;chat_id&#x60; in the Messaging API. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **add_community_member**
> AddGroupMember200Response add_community_member(community_id, account_id, add_group_member_request)

Add a Member to a Community

Adds a member to a community the account owner administers. WhatsApp returns 409 for an existing member, 422 for a number without a WhatsApp account, or 403 when the user’s privacy settings prevent adding them. Send the invite link when the user’s settings require it.

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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    add_group_member_request = unipile.AddGroupMemberRequest() # AddGroupMemberRequest | The user to add to the group or community.

    try:
        # Add a Member to a Community
        api_response = api_instance.add_community_member(community_id, account_id, add_group_member_request)
        print("The response of CommunitiesApi->add_community_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->add_community_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
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

# **cancel_community_join_request**
> CancelCommunityJoinRequest200Response cancel_community_join_request(community_id, request_id, account_id)

Refuse a Community's Join Request

Refuses a request to join a community the account owner administers.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.cancel_community_join_request200_response import CancelCommunityJoinRequest200Response
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    request_id = 'request_id_example' # str | The ID of the request. Use an ID returned by *List all Community's Join Requests*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Refuse a Community's Join Request
        api_response = api_instance.cancel_community_join_request(community_id, request_id, account_id)
        print("The response of CommunitiesApi->cancel_community_join_request:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->cancel_community_join_request: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **request_id** | **str**| The ID of the request. Use an ID returned by *List all Community&#39;s Join Requests*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**CancelCommunityJoinRequest200Response**](CancelCommunityJoinRequest200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The request was refused. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_community**
> PerformCommunitiesSearch200ResponseDataInner create_community(account_id, create_community_request)

Create a Community

Creates a community administered by the account owner. WhatsApp also creates an announcement chat and a General chat. Their IDs are included in `chat_ids` when available. The name has 1 to 100 characters and the description has at most 2048.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_community_request import CreateCommunityRequest
from unipile.models.perform_communities_search200_response_data_inner import PerformCommunitiesSearch200ResponseDataInner
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
    api_instance = unipile.CommunitiesApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_community_request = unipile.CreateCommunityRequest() # CreateCommunityRequest | The community to create.

    try:
        # Create a Community
        api_response = api_instance.create_community(account_id, create_community_request)
        print("The response of CommunitiesApi->create_community:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->create_community: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_community_request** | [**CreateCommunityRequest**](CreateCommunityRequest.md)| The community to create. | 

### Return type

[**PerformCommunitiesSearch200ResponseDataInner**](PerformCommunitiesSearch200ResponseDataInner.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | A community whose members have access to linked group chats. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_community**
> PerformCommunitiesSearch200ResponseDataInner get_community(community_id, account_id)

Get a Community

Returns a community and the account owner’s membership. The `chat_ids` array contains the known announcement and linked chat IDs. An invitation code or URL-encoded link in `community_id` previews a community before joining.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_communities_search200_response_data_inner import PerformCommunitiesSearch200ResponseDataInner
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The community ID returned by *Perform Communities Search*, or an invitation code or URL-encoded link to preview the community.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Community
        api_response = api_instance.get_community(community_id, account_id)
        print("The response of CommunitiesApi->get_community:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->get_community: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The community ID returned by *Perform Communities Search*, or an invitation code or URL-encoded link to preview the community. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**PerformCommunitiesSearch200ResponseDataInner**](PerformCommunitiesSearch200ResponseDataInner.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | A community whose members have access to linked group chats. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_community_chats_list**
> GetCommunityChatsList200Response get_community_chats_list(community_id, account_id)

List all Community's Chats

Lists the announcement chat and other linked conversations in one page. Use the returned `id` in the Messaging API once the account has access to the conversation.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_community_chats_list200_response import GetCommunityChatsList200Response
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # List all Community's Chats
        api_response = api_instance.get_community_chats_list(community_id, account_id)
        print("The response of CommunitiesApi->get_community_chats_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->get_community_chats_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetCommunityChatsList200Response**](GetCommunityChatsList200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The chats linked to the community. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_community_invite_link**
> GetChatInviteLink200Response get_community_invite_link(community_id, account_id)

Get a Community's Invite Link

Returns the invitation link for a community the account owner administers. Use its `code` or link to preview or join the community.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_chat_invite_link200_response import GetChatInviteLink200Response
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Community's Invite Link
        api_response = api_instance.get_community_invite_link(community_id, account_id)
        print("The response of CommunitiesApi->get_community_invite_link:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->get_community_invite_link: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetChatInviteLink200Response**](GetChatInviteLink200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The link that invites people to join a group chat or a community. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_community_join_requests_list**
> GetCommunityJoinRequestsList200Response get_community_join_requests_list(community_id, account_id)

List all Community's Join Requests

Returns all pending requests in one page for a community the account owner administers when `join_approval` is enabled.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_community_join_requests_list200_response import GetCommunityJoinRequestsList200Response
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # List all Community's Join Requests
        api_response = api_instance.get_community_join_requests_list(community_id, account_id)
        print("The response of CommunitiesApi->get_community_join_requests_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->get_community_join_requests_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetCommunityJoinRequestsList200Response**](GetCommunityJoinRequestsList200Response.md)

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

# **get_community_members_list**
> GetGroupMembersList200Response get_community_members_list(community_id, account_id, cursor=cursor, limit=limit)

List all Community's Members

Returns community members and their admin status. Use *List all Chat Participants* for the members of an individual conversation.

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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    cursor = 'cursor_example' # str | A cursor used for pagination. Use `next_cursor` given by the previous page of the list. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # List all Community's Members
        api_response = api_instance.get_community_members_list(community_id, account_id, cursor=cursor, limit=limit)
        print("The response of CommunitiesApi->get_community_members_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->get_community_members_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
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

# **join_community**
> JoinCommunity200Response join_community(community_id, account_id)

Join a Community

Joins a community using its invitation code or URL-encoded link as `community_id`. If approval is required, the membership stays `pending` until an admin approves it. WhatsApp also joins the announcement chat. WhatsApp may return 403 if an admin previously removed the account from the community. Use *Join a Chat* for invitations to individual conversations.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.join_community200_response import JoinCommunity200Response
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The invitation code or URL-encoded invitation link to the community.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Join a Community
        api_response = api_instance.join_community(community_id, account_id)
        print("The response of CommunitiesApi->join_community:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->join_community: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The invitation code or URL-encoded invitation link to the community. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**JoinCommunity200Response**](JoinCommunity200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The result of the request to join the community. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **leave_community**
> LeaveCommunity200Response leave_community(community_id, account_id)

Leave a Community

Leaves a community and its linked conversations. On WhatsApp, the creator cannot leave the community (403).

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.leave_community200_response import LeaveCommunity200Response
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Leave a Community
        api_response = api_instance.leave_community(community_id, account_id)
        print("The response of CommunitiesApi->leave_community:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->leave_community: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**LeaveCommunity200Response**](LeaveCommunity200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The account owner left the community. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_communities_search**
> PerformCommunitiesSearch200Response perform_communities_search(account_id, perform_communities_search_request, cursor=cursor, limit=limit)

Perform Communities Search

Searches by name among the communities the account owner belongs to. Send the same body with `cursor` to get the next page. Available for WhatsApp.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_communities_search200_response import PerformCommunitiesSearch200Response
from unipile.models.perform_communities_search_request import PerformCommunitiesSearchRequest
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
    api_instance = unipile.CommunitiesApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    perform_communities_search_request = unipile.PerformCommunitiesSearchRequest() # PerformCommunitiesSearchRequest | The criteria of the search.
    cursor = 'cursor_example' # str | A cursor used for pagination. Use `next_cursor` given by the previous page of the list. (optional)
    limit = 20 # int | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # Perform Communities Search
        api_response = api_instance.perform_communities_search(account_id, perform_communities_search_request, cursor=cursor, limit=limit)
        print("The response of CommunitiesApi->perform_communities_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->perform_communities_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **perform_communities_search_request** | [**PerformCommunitiesSearchRequest**](PerformCommunitiesSearchRequest.md)| The criteria of the search. | 
 **cursor** | **str**| A cursor used for pagination. Use &#x60;next_cursor&#x60; given by the previous page of the list. | [optional] 
 **limit** | **int**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]

### Return type

[**PerformCommunitiesSearch200Response**](PerformCommunitiesSearch200Response.md)

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

# **remove_community_chat**
> RemoveCommunityChat200Response remove_community_chat(community_id, chat_id, account_id)

Remove a Chat from a Community

Detaches a conversation from a community the account owner administers. The chat and its members are retained. The announcement chat remains linked.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.remove_community_chat200_response import RemoveCommunityChat200Response
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    chat_id = 'chat_id_example' # str | The ID of the chat linked to the community. Use the `id` returned by *List all Community's Chats*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Remove a Chat from a Community
        api_response = api_instance.remove_community_chat(community_id, chat_id, account_id)
        print("The response of CommunitiesApi->remove_community_chat:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->remove_community_chat: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **chat_id** | **str**| The ID of the chat linked to the community. Use the &#x60;id&#x60; returned by *List all Community&#39;s Chats*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**RemoveCommunityChat200Response**](RemoveCommunityChat200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The chat was detached from the community. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **remove_community_member**
> RemoveCommunityMember200Response remove_community_member(community_id, user_id, account_id)

Remove a Member from a Community

Removes a member from a community the account owner administers and from its linked conversations.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.remove_community_member200_response import RemoveCommunityMember200Response
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    user_id = 'user_id_example' # str | The ID of the member. Use an ID returned by *List all Community's Members*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Remove a Member from a Community
        api_response = api_instance.remove_community_member(community_id, user_id, account_id)
        print("The response of CommunitiesApi->remove_community_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->remove_community_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **user_id** | **str**| The ID of the member. Use an ID returned by *List all Community&#39;s Members*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**RemoveCommunityMember200Response**](RemoveCommunityMember200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The member was removed. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **reset_community_invite_link**
> GetChatInviteLink200Response reset_community_invite_link(community_id, account_id)

Reset a Community's Invite Link

Replaces the invitation link for a community the account owner administers. The previous link stops working.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_chat_invite_link200_response import GetChatInviteLink200Response
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Reset a Community's Invite Link
        api_response = api_instance.reset_community_invite_link(community_id, account_id)
        print("The response of CommunitiesApi->reset_community_invite_link:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->reset_community_invite_link: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetChatInviteLink200Response**](GetChatInviteLink200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The link that invites people to join a group chat or a community. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_community**
> PerformCommunitiesSearch200ResponseDataInner update_community(community_id, account_id, update_community_request=update_community_request)

Update a Community

Updates a community the account owner administers and returns it. On WhatsApp, names have 1 to 100 characters and descriptions have at most 2048.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_communities_search200_response_data_inner import PerformCommunitiesSearch200ResponseDataInner
from unipile.models.update_community_request import UpdateCommunityRequest
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_community_request = unipile.UpdateCommunityRequest() # UpdateCommunityRequest | The changes to make to the community. Fields left out are kept. (optional)

    try:
        # Update a Community
        api_response = api_instance.update_community(community_id, account_id, update_community_request=update_community_request)
        print("The response of CommunitiesApi->update_community:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->update_community: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_community_request** | [**UpdateCommunityRequest**](UpdateCommunityRequest.md)| The changes to make to the community. Fields left out are kept. | [optional] 

### Return type

[**PerformCommunitiesSearch200ResponseDataInner**](PerformCommunitiesSearch200ResponseDataInner.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | A community whose members have access to linked group chats. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_community_member**
> UpdateCommunityMember200Response update_community_member(community_id, user_id, account_id, update_community_member_request)

Update a Member of a Community

Grants or revokes admin status for a community member.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.update_community_member200_response import UpdateCommunityMember200Response
from unipile.models.update_community_member_request import UpdateCommunityMemberRequest
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
    api_instance = unipile.CommunitiesApi(api_client)
    community_id = 'community_id_example' # str | The ID of the community. Use IDs from *Perform Communities Search* method responses.
    user_id = 'user_id_example' # str | The ID of the member. Use an ID returned by *List all Community's Members*.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_community_member_request = unipile.UpdateCommunityMemberRequest() # UpdateCommunityMemberRequest | The changes to make to the member.

    try:
        # Update a Member of a Community
        api_response = api_instance.update_community_member(community_id, user_id, account_id, update_community_member_request)
        print("The response of CommunitiesApi->update_community_member:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CommunitiesApi->update_community_member: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **community_id** | **str**| The ID of the community. Use IDs from *Perform Communities Search* method responses. | 
 **user_id** | **str**| The ID of the member. Use an ID returned by *List all Community&#39;s Members*. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_community_member_request** | [**UpdateCommunityMemberRequest**](UpdateCommunityMemberRequest.md)| The changes to make to the member. | 

### Return type

[**UpdateCommunityMember200Response**](UpdateCommunityMember200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | The member was updated. |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

