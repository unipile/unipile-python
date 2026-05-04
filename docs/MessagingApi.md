# unipile.MessagingApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**add_message_reaction**](MessagingApi.md#add_message_reaction) | **POST** /v2/{account_id}/chats/{chat_id}/messages/{message_id}/reactions | Add a Message Reaction
[**add_participant**](MessagingApi.md#add_participant) | **POST** /v2/{account_id}/chats/{chat_id}/participants | Add a Chat Participant
[**delete_chat**](MessagingApi.md#delete_chat) | **DELETE** /v2/{account_id}/chats/{chat_id} | Delete a Chat
[**delete_message**](MessagingApi.md#delete_message) | **DELETE** /v2/{account_id}/chats/{chat_id}/messages/{message_id} | Delete a Message
[**forward_message**](MessagingApi.md#forward_message) | **POST** /v2/{account_id}/chats/{chat_id}/messages/{message_id}/forward | Forward a Message
[**get_attachment**](MessagingApi.md#get_attachment) | **GET** /v2/{account_id}/chats/{chat_id}/messages/{message_id}/attachments/{attachment_id} | Get a Message Attachment
[**get_chat**](MessagingApi.md#get_chat) | **GET** /v2/{account_id}/chats/{chat_id} | Get a Chat
[**get_chats_list**](MessagingApi.md#get_chats_list) | **GET** /v2/{account_id}/chats | List all Chats
[**get_inbox_chats_list**](MessagingApi.md#get_inbox_chats_list) | **GET** /v2/{account_id}/inboxes/{inbox_id}/chats | List Inbox Chats
[**get_inboxes_list**](MessagingApi.md#get_inboxes_list) | **GET** /v2/{account_id}/inboxes | List all Inboxes
[**get_message**](MessagingApi.md#get_message) | **GET** /v2/{account_id}/chats/{chat_id}/messages/{message_id} | Get a Message
[**get_message_reactions_list**](MessagingApi.md#get_message_reactions_list) | **GET** /v2/{account_id}/chats/{chat_id}/messages/{message_id}/reactions | List all Message&#39;s Reactions
[**get_messages_list**](MessagingApi.md#get_messages_list) | **GET** /v2/{account_id}/chats/{chat_id}/messages | List all Chat Messages
[**get_participants_list**](MessagingApi.md#get_participants_list) | **GET** /v2/{account_id}/chats/{chat_id}/participants | List all Chat Participants
[**get_user_chat**](MessagingApi.md#get_user_chat) | **GET** /v2/{account_id}/users/{user_id}/chat | Get a User Chat
[**modify_message**](MessagingApi.md#modify_message) | **POST** /v2/{account_id}/chats/{chat_id}/messages/{message_id}/modify | Modify a Message
[**read_message**](MessagingApi.md#read_message) | **POST** /v2/{account_id}/chats/{chat_id}/messages/{message_id}/read | Read a Message
[**remove_message_reaction**](MessagingApi.md#remove_message_reaction) | **DELETE** /v2/{account_id}/chats/{chat_id}/messages/{message_id}/reactions | Remove a Message Reaction
[**remove_participant**](MessagingApi.md#remove_participant) | **DELETE** /v2/{account_id}/chats/{chat_id}/participants/{user_id} | Remove a Chat Participant
[**send_message**](MessagingApi.md#send_message) | **POST** /v2/{account_id}/chats/{chat_id}/messages/send | Send a Message
[**set_composing_status**](MessagingApi.md#set_composing_status) | **POST** /v2/{account_id}/chats/{chat_id}/composing | Set Composing Status
[**set_presence**](MessagingApi.md#set_presence) | **POST** /v2/{account_id}/presence | Set Presence
[**start_chat**](MessagingApi.md#start_chat) | **POST** /v2/{account_id}/chats/send | Start a Chat
[**start_chat_from_inbox**](MessagingApi.md#start_chat_from_inbox) | **POST** /v2/{account_id}/inboxes/{inbox_id}/chats/send | Start a Chat from Inbox
[**update_chat**](MessagingApi.md#update_chat) | **PATCH** /v2/{account_id}/chats/{chat_id} | Update a Chat


# **add_message_reaction**
> AddMessageReaction200Response add_message_reaction(chat_id, message_id, account_id, add_message_reaction_request)

Add a Message Reaction

Adds a reaction to a message. Some providers only allow the use of a limited list of emojis, trying to react with an unsupported emoji will fail.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.add_message_reaction200_response import AddMessageReaction200Response
from unipile.models.add_message_reaction_request import AddMessageReactionRequest
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat where the message is.
    message_id = 'message_id_example' # str | The ID of the Message to add the reaction to.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    add_message_reaction_request = unipile.AddMessageReactionRequest() # AddMessageReactionRequest | 

    try:
        # Add a Message Reaction
        api_response = api_instance.add_message_reaction(chat_id, message_id, account_id, add_message_reaction_request)
        print("The response of MessagingApi->add_message_reaction:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->add_message_reaction: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat where the message is. | 
 **message_id** | **str**| The ID of the Message to add the reaction to. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **add_message_reaction_request** | [**AddMessageReactionRequest**](AddMessageReactionRequest.md)|  | 

### Return type

[**AddMessageReaction200Response**](AddMessageReaction200Response.md)

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

# **add_participant**
> AddParticipant200Response add_participant(chat_id, account_id, add_participant_request)

Add a Chat Participant

Adds a new user as participant of chat if you have the rights to. Providers might requires an admin role or some permissions.
      <br />
      Trying to add a participant into a 1to1 chat can fail depending on the provider.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.add_participant200_response import AddParticipant200Response
from unipile.models.add_participant_request import AddParticipantRequest
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat to add the participant to.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    add_participant_request = unipile.AddParticipantRequest() # AddParticipantRequest | 

    try:
        # Add a Chat Participant
        api_response = api_instance.add_participant(chat_id, account_id, add_participant_request)
        print("The response of MessagingApi->add_participant:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->add_participant: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat to add the participant to. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **add_participant_request** | [**AddParticipantRequest**](AddParticipantRequest.md)|  | 

### Return type

[**AddParticipant200Response**](AddParticipant200Response.md)

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

# **delete_chat**
> delete_chat(chat_id, account_id)

Delete a Chat

Deletes a chat if supported by the provider.

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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | ID of the Chat to delete.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Delete a Chat
        api_instance.delete_chat(chat_id, account_id)
    except Exception as e:
        print("Exception when calling MessagingApi->delete_chat: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| ID of the Chat to delete. | 
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

# **delete_message**
> delete_message(chat_id, message_id, account_id)

Delete a Message

Deletes one of your own messages. Depending of the provider, the message might still be visible as deleted.
      <br />
      Trying to delete the message of another user will fail. 

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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat where the message is.
    message_id = 'message_id_example' # str | The ID of the Message to delete.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Delete a Message
        api_instance.delete_message(chat_id, message_id, account_id)
    except Exception as e:
        print("Exception when calling MessagingApi->delete_message: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat where the message is. | 
 **message_id** | **str**| The ID of the Message to delete. | 
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

# **forward_message**
> ForwardMessage200Response forward_message(chat_id, message_id, account_id, forward_message_request)

Forward a Message

Forwards a message to another chat.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.forward_message200_response import ForwardMessage200Response
from unipile.models.forward_message_request import ForwardMessageRequest
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat where the message is.
    message_id = 'message_id_example' # str | The ID of the Message to forward.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    forward_message_request = unipile.ForwardMessageRequest() # ForwardMessageRequest | 

    try:
        # Forward a Message
        api_response = api_instance.forward_message(chat_id, message_id, account_id, forward_message_request)
        print("The response of MessagingApi->forward_message:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->forward_message: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat where the message is. | 
 **message_id** | **str**| The ID of the Message to forward. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **forward_message_request** | [**ForwardMessageRequest**](ForwardMessageRequest.md)|  | 

### Return type

[**ForwardMessage200Response**](ForwardMessage200Response.md)

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

# **get_attachment**
> get_attachment(chat_id, message_id, attachment_id, account_id)

Get a Message Attachment

Download the attachment file of a message.

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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat where the parent message of the attachment is.
    message_id = 'message_id_example' # str | The ID of the Message where the attachment is.
    attachment_id = 'attachment_id_example' # str | The ID of the Attachment to retrieve.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Message Attachment
        api_instance.get_attachment(chat_id, message_id, attachment_id, account_id)
    except Exception as e:
        print("Exception when calling MessagingApi->get_attachment: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat where the parent message of the attachment is. | 
 **message_id** | **str**| The ID of the Message where the attachment is. | 
 **attachment_id** | **str**| The ID of the Attachment to retrieve. | 
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
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_chat**
> GetChat200Response get_chat(chat_id, account_id)

Get a Chat

Retrieves a Chat object.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_chat200_response import GetChat200Response
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | ID of the Chat to retrieve.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Chat
        api_response = api_instance.get_chat(chat_id, account_id)
        print("The response of MessagingApi->get_chat:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->get_chat: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| ID of the Chat to retrieve. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetChat200Response**](GetChat200Response.md)

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

# **get_chats_list**
> GetChatsList200Response get_chats_list(account_id, offset=offset, limit=limit, cursor=cursor, type=type, before=before, after=after, is_archived=is_archived, is_unread=is_unread)

List all Chats

Returns a list of account's chats, whatever the inbox they belong to. The chats are returned sorted by their last message date, with the most recent appearing first. You might want to use the <a href="https://developer.unipile.com/v2.0/reference/get_v2-account-id-inboxes-inbox-id-chats">List inbox Chats</a> instead if not supported by the provider. Filters are applied with an AND logic if supported by the provider.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_chats_list200_response import GetChatsList200Response
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
    api_instance = unipile.MessagingApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)
    type = 'type_example' # str | Return only chats of the given type (if supported by the provider).         - `1to1` is a 1to1 chat.         - `group` is a group chat.         - `channel` is a channel chat. (optional)
    before = 'before_example' # str | A filter to target items created before the datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). (optional)
    after = 'after_example' # str | A filter to target items created after the datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ).. (optional)
    is_archived = True # bool | Return only chats of the given archived status (if supported by the provider). (optional)
    is_unread = True # bool | Return only chats of the given unread status (if supported by the provider). (optional)

    try:
        # List all Chats
        api_response = api_instance.get_chats_list(account_id, offset=offset, limit=limit, cursor=cursor, type=type, before=before, after=after, is_archived=is_archived, is_unread=is_unread)
        print("The response of MessagingApi->get_chats_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->get_chats_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 
 **type** | **str**| Return only chats of the given type (if supported by the provider).         - &#x60;1to1&#x60; is a 1to1 chat.         - &#x60;group&#x60; is a group chat.         - &#x60;channel&#x60; is a channel chat. | [optional] 
 **before** | **str**| A filter to target items created before the datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
 **after** | **str**| A filter to target items created after the datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ).. | [optional] 
 **is_archived** | **bool**| Return only chats of the given archived status (if supported by the provider). | [optional] 
 **is_unread** | **bool**| Return only chats of the given unread status (if supported by the provider). | [optional] 

### Return type

[**GetChatsList200Response**](GetChatsList200Response.md)

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

# **get_inbox_chats_list**
> GetChatsList200Response get_inbox_chats_list(inbox_id, account_id, offset=offset, limit=limit, cursor=cursor, type=type, before=before, after=after, is_archived=is_archived, is_unread=is_unread)

List Inbox Chats

Returns a list of account's chats from a specific inbox. The chats are returned sorted by their last message date, with the most recent appearing first. Filters are applied with an AND logic if supported by the provider.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_chats_list200_response import GetChatsList200Response
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
    api_instance = unipile.MessagingApi(api_client)
    inbox_id = 'inbox_id_example' # str | ID of the Inbox to retrieve Chats from. Use <a href=\"https://developer.unipile.com/v2.0/reference/get_v2-account-id-inboxes\">List all Inboxes</a> to get the ID of an inbox.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)
    type = 'type_example' # str | Return only chats of the given type (if supported by the provider).         - `1to1` is a 1to1 chat.         - `group` is a group chat.         - `channel` is a channel chat. (optional)
    before = 'before_example' # str | A filter to target items created before the datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). (optional)
    after = 'after_example' # str | A filter to target items created after the datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ).. (optional)
    is_archived = True # bool | Return only chats of the given archived status (if supported by the provider). (optional)
    is_unread = True # bool | Return only chats of the given unread status (if supported by the provider). (optional)

    try:
        # List Inbox Chats
        api_response = api_instance.get_inbox_chats_list(inbox_id, account_id, offset=offset, limit=limit, cursor=cursor, type=type, before=before, after=after, is_archived=is_archived, is_unread=is_unread)
        print("The response of MessagingApi->get_inbox_chats_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->get_inbox_chats_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inbox_id** | **str**| ID of the Inbox to retrieve Chats from. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-inboxes\&quot;&gt;List all Inboxes&lt;/a&gt; to get the ID of an inbox. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 
 **type** | **str**| Return only chats of the given type (if supported by the provider).         - &#x60;1to1&#x60; is a 1to1 chat.         - &#x60;group&#x60; is a group chat.         - &#x60;channel&#x60; is a channel chat. | [optional] 
 **before** | **str**| A filter to target items created before the datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
 **after** | **str**| A filter to target items created after the datetime (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ).. | [optional] 
 **is_archived** | **bool**| Return only chats of the given archived status (if supported by the provider). | [optional] 
 **is_unread** | **bool**| Return only chats of the given unread status (if supported by the provider). | [optional] 

### Return type

[**GetChatsList200Response**](GetChatsList200Response.md)

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

# **get_inboxes_list**
> GetInboxesList200Response get_inboxes_list(account_id)

List all Inboxes

Returns a list of the account's Inboxes.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_inboxes_list200_response import GetInboxesList200Response
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
    api_instance = unipile.MessagingApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # List all Inboxes
        api_response = api_instance.get_inboxes_list(account_id)
        print("The response of MessagingApi->get_inboxes_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->get_inboxes_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetInboxesList200Response**](GetInboxesList200Response.md)

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

# **get_message**
> GetMessage200Response get_message(chat_id, message_id, account_id)

Get a Message

Retrieves a message object.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_message200_response import GetMessage200Response
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat where the message is.
    message_id = 'message_id_example' # str | The ID of the Message to retrieve.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Message
        api_response = api_instance.get_message(chat_id, message_id, account_id)
        print("The response of MessagingApi->get_message:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->get_message: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat where the message is. | 
 **message_id** | **str**| The ID of the Message to retrieve. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetMessage200Response**](GetMessage200Response.md)

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

# **get_message_reactions_list**
> GetMessageReactionsList200Response get_message_reactions_list(chat_id, message_id, account_id, offset=offset, limit=limit, cursor=cursor)

List all Message's Reactions

Returns the list of reactions made to a message. Reaction counts are given with the Message object. This is useful to show a detailed list of all reactions and their author.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_message_reactions_list200_response import GetMessageReactionsList200Response
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat where the message is.
    message_id = 'message_id_example' # str | The ID of the Message to retrieve reactions from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all Message's Reactions
        api_response = api_instance.get_message_reactions_list(chat_id, message_id, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of MessagingApi->get_message_reactions_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->get_message_reactions_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat where the message is. | 
 **message_id** | **str**| The ID of the Message to retrieve reactions from. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetMessageReactionsList200Response**](GetMessageReactionsList200Response.md)

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

# **get_messages_list**
> GetMessagesList200Response get_messages_list(chat_id, account_id, before=before, after=after, user_id=user_id, offset=offset, limit=limit, cursor=cursor)

List all Chat Messages

Returns a list of messages in a chat. The messages are returned sorted by their timestamp, with the most recent appearing first.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_messages_list200_response import GetMessagesList200Response
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat to retrieve messages from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    before = 'before_example' # str | Filter to only return messages sent before the given timestamp (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). (optional)
    after = 'after_example' # str | Filter to only return messages sent after the given timestamp (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). (optional)
    user_id = 'user_id_example' # str | Filter to only return messages sent by the given User. (optional)
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all Chat Messages
        api_response = api_instance.get_messages_list(chat_id, account_id, before=before, after=after, user_id=user_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of MessagingApi->get_messages_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->get_messages_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat to retrieve messages from. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **before** | **str**| Filter to only return messages sent before the given timestamp (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
 **after** | **str**| Filter to only return messages sent after the given timestamp (exclusive). Must be an ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
 **user_id** | **str**| Filter to only return messages sent by the given User. | [optional] 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetMessagesList200Response**](GetMessagesList200Response.md)

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

# **get_participants_list**
> GetParticipantsList200Response get_participants_list(chat_id, account_id, offset=offset, limit=limit, cursor=cursor)

List all Chat Participants

Returns a list of participants in the specified group chat. For 1to1 chats, the unique participant is given in the chat object.
      <br />
      Trying to retrieve the list of participants of a 1to1 chat will fail.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_participants_list200_response import GetParticipantsList200Response
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | ID of the Chat to retrieve participants from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all Chat Participants
        api_response = api_instance.get_participants_list(chat_id, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of MessagingApi->get_participants_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->get_participants_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| ID of the Chat to retrieve participants from. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetParticipantsList200Response**](GetParticipantsList200Response.md)

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

# **get_user_chat**
> GetUserChat200Response get_user_chat(user_id, account_id)

Get a User Chat

Resolves chat identifiers associated with the specified User. Depending on the provider, the result may include chats with or without message history, and may return multiple matches across inboxes or contexts.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_user_chat200_response import GetUserChat200Response
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
    api_instance = unipile.MessagingApi(api_client)
    user_id = 'user_id_example' # str | ID of the User whose existing 1to1 Chat should be retrieved.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a User Chat
        api_response = api_instance.get_user_chat(user_id, account_id)
        print("The response of MessagingApi->get_user_chat:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->get_user_chat: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| ID of the User whose existing 1to1 Chat should be retrieved. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetUserChat200Response**](GetUserChat200Response.md)

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

# **modify_message**
> ModifyMessage200Response modify_message(chat_id, message_id, account_id, modify_message_request)

Modify a Message

Modifies one of the account's owner messages.
      <br/>
      Trying to modify the message of another user will fail.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.modify_message200_response import ModifyMessage200Response
from unipile.models.modify_message_request import ModifyMessageRequest
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat where the message is.
    message_id = 'message_id_example' # str | The ID of the Message to modify.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    modify_message_request = unipile.ModifyMessageRequest() # ModifyMessageRequest | 

    try:
        # Modify a Message
        api_response = api_instance.modify_message(chat_id, message_id, account_id, modify_message_request)
        print("The response of MessagingApi->modify_message:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->modify_message: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat where the message is. | 
 **message_id** | **str**| The ID of the Message to modify. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **modify_message_request** | [**ModifyMessageRequest**](ModifyMessageRequest.md)|  | 

### Return type

[**ModifyMessage200Response**](ModifyMessage200Response.md)

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

# **read_message**
> ReadMessage200Response read_message(chat_id, message_id, account_id)

Read a Message

Marks a message sent in the chat by another user as read by you.
        Trying to mark your own messages as read will fail.
        This does not affect the read status of the chat. Use <a href="https://developer.unipile.com/v2.0/reference/patch_v2-account-id-chats-chat-id">Update a Chat</a> to mark a chat as read. 

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.read_message200_response import ReadMessage200Response
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat where the message is.
    message_id = 'message_id_example' # str | The ID of the Message to mark as read.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Read a Message
        api_response = api_instance.read_message(chat_id, message_id, account_id)
        print("The response of MessagingApi->read_message:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->read_message: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat where the message is. | 
 **message_id** | **str**| The ID of the Message to mark as read. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**ReadMessage200Response**](ReadMessage200Response.md)

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

# **remove_message_reaction**
> RemoveMessageReaction200Response remove_message_reaction(chat_id, message_id, account_id, remove_message_reaction_request)

Remove a Message Reaction

Removes a reaction of the account's owner from a message. Trying to remove a reaction from another user will fail.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.remove_message_reaction200_response import RemoveMessageReaction200Response
from unipile.models.remove_message_reaction_request import RemoveMessageReactionRequest
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat where the message is.
    message_id = 'message_id_example' # str | The ID of the Message where the reaction is.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    remove_message_reaction_request = unipile.RemoveMessageReactionRequest() # RemoveMessageReactionRequest | 

    try:
        # Remove a Message Reaction
        api_response = api_instance.remove_message_reaction(chat_id, message_id, account_id, remove_message_reaction_request)
        print("The response of MessagingApi->remove_message_reaction:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->remove_message_reaction: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat where the message is. | 
 **message_id** | **str**| The ID of the Message where the reaction is. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **remove_message_reaction_request** | [**RemoveMessageReactionRequest**](RemoveMessageReactionRequest.md)|  | 

### Return type

[**RemoveMessageReaction200Response**](RemoveMessageReaction200Response.md)

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

# **remove_participant**
> RemoveParticipant200Response remove_participant(chat_id, user_id, account_id)

Remove a Chat Participant

Removes a participant user from a chat if you have the rights to. Providers might requires an admin role or some permissions.
      <br />
      Trying to remove a participant from a 1to1 chat will fail.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.remove_participant200_response import RemoveParticipant200Response
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat to remove the participant from.
    user_id = 'user_id_example' # str | The ID of the User to remove from the chat.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Remove a Chat Participant
        api_response = api_instance.remove_participant(chat_id, user_id, account_id)
        print("The response of MessagingApi->remove_participant:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->remove_participant: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat to remove the participant from. | 
 **user_id** | **str**| The ID of the User to remove from the chat. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**RemoveParticipant200Response**](RemoveParticipant200Response.md)

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

# **send_message**
> SendMessage200Response send_message(chat_id, account_id, send_message_request)

Send a Message

Sends a message in the specified chat.
      <br/>
      Use <a href="https://developer.unipile.com/v2.0/reference/post_v2-account-id-chats-send">Start a Chat</a> if you don't have a conversation with the wanted user(s) yet.
      <br/>
      Multipart supported, refer to <a href="https://developer.unipile.com/v2.0/reference/api-usage#sending-files">Sending Files</a>.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.send_message200_response import SendMessage200Response
from unipile.models.send_message_request import SendMessageRequest
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | The ID of the Chat to send the message to.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    send_message_request = unipile.SendMessageRequest() # SendMessageRequest | 

    try:
        # Send a Message
        api_response = api_instance.send_message(chat_id, account_id, send_message_request)
        print("The response of MessagingApi->send_message:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->send_message: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| The ID of the Chat to send the message to. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **send_message_request** | [**SendMessageRequest**](SendMessageRequest.md)|  | 

### Return type

[**SendMessage200Response**](SendMessage200Response.md)

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

# **set_composing_status**
> SetComposingStatus200Response set_composing_status(action, chat_id, account_id)

Set Composing Status

Sets the composing status of the user in a chat.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.set_composing_status200_response import SetComposingStatus200Response
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
    api_instance = unipile.MessagingApi(api_client)
    action = 'action_example' # str | The composing status of a user in a chat.     - `typing` if the user is typing / sending a message. This presence must target a chat.     - `recording` if the user is recording a voice note. This presence must target a chat.
    chat_id = 'chat_id_example' # str | ID of the Chat where the composing action is taking place.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Set Composing Status
        api_response = api_instance.set_composing_status(action, chat_id, account_id)
        print("The response of MessagingApi->set_composing_status:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->set_composing_status: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **action** | **str**| The composing status of a user in a chat.     - &#x60;typing&#x60; if the user is typing / sending a message. This presence must target a chat.     - &#x60;recording&#x60; if the user is recording a voice note. This presence must target a chat. | 
 **chat_id** | **str**| ID of the Chat where the composing action is taking place. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**SetComposingStatus200Response**](SetComposingStatus200Response.md)

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

# **set_presence**
> SetPresence200Response set_presence(account_id, set_presence_request)

Set Presence

Sets the presence of the user.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.set_presence200_response import SetPresence200Response
from unipile.models.set_presence_request import SetPresenceRequest
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
    api_instance = unipile.MessagingApi(api_client)
    account_id = 'account_id_example' # str | 
    set_presence_request = unipile.SetPresenceRequest() # SetPresenceRequest | 

    try:
        # Set Presence
        api_response = api_instance.set_presence(account_id, set_presence_request)
        print("The response of MessagingApi->set_presence:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->set_presence: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**|  | 
 **set_presence_request** | [**SetPresenceRequest**](SetPresenceRequest.md)|  | 

### Return type

[**SetPresence200Response**](SetPresence200Response.md)

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

# **start_chat**
> StartChat200Response start_chat(account_id, start_chat_request)

Start a Chat

Starts a new 1to1 or group chat by sending the first message.
      <br/>
      Use <a href="https://developer.unipile.com/v2.0/reference/post_v2-account-id-chats-chat-id-messages-send">Send a Message</a> if a conversation already exist with the wanted user(s).
      <br/>
      Use <a href="https://developer.unipile.com/v2.0/reference/post_v2-account-id-inboxes-inbox-id-chats">Start a Chat from Inbox</a> if the provider uses the inbox concept.
      <br/>
      Multipart supported, refer to <a href="https://developer.unipile.com/v2.0/reference/api-usage#sending-files">Sending Files</a>.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.start_chat200_response import StartChat200Response
from unipile.models.start_chat_request import StartChatRequest
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
    api_instance = unipile.MessagingApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    start_chat_request = unipile.StartChatRequest() # StartChatRequest | 

    try:
        # Start a Chat
        api_response = api_instance.start_chat(account_id, start_chat_request)
        print("The response of MessagingApi->start_chat:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->start_chat: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **start_chat_request** | [**StartChatRequest**](StartChatRequest.md)|  | 

### Return type

[**StartChat200Response**](StartChat200Response.md)

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

# **start_chat_from_inbox**
> StartChat200Response start_chat_from_inbox(inbox_id, account_id, start_chat_from_inbox_request)

Start a Chat from Inbox

Starts a new 1to1 or group chat in the given inbox by sending the first message.
      <br/>
      Use <a href="https://developer.unipile.com/v2.0/reference/post_v2-account-id-chats-chat-id-messages-send">Send a Message</a> if a conversation already exist with the wanted user(s).
      <br/>
      Use <a href="https://developer.unipile.com/v2.0/reference/post_v2-account-id-chats-send">Start a Chat</a> instead if the provider does not use the inbox concept.
      
      <br/>
      Multipart supported, refer to <a href="https://developer.unipile.com/v2.0/reference/api-usage#sending-files">Sending Files</a>.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.start_chat200_response import StartChat200Response
from unipile.models.start_chat_from_inbox_request import StartChatFromInboxRequest
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
    api_instance = unipile.MessagingApi(api_client)
    inbox_id = 'inbox_id_example' # str | ID of the Inbox to start the Chat in. Use <a href=\"https://developer.unipile.com/v2.0/reference/get_v2-account-id-inboxes\">List all Inboxes</a> to get the ID of an inbox.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    start_chat_from_inbox_request = unipile.StartChatFromInboxRequest() # StartChatFromInboxRequest | 

    try:
        # Start a Chat from Inbox
        api_response = api_instance.start_chat_from_inbox(inbox_id, account_id, start_chat_from_inbox_request)
        print("The response of MessagingApi->start_chat_from_inbox:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->start_chat_from_inbox: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inbox_id** | **str**| ID of the Inbox to start the Chat in. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-inboxes\&quot;&gt;List all Inboxes&lt;/a&gt; to get the ID of an inbox. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **start_chat_from_inbox_request** | [**StartChatFromInboxRequest**](StartChatFromInboxRequest.md)|  | 

### Return type

[**StartChat200Response**](StartChat200Response.md)

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

# **update_chat**
> GetChat200Response update_chat(chat_id, account_id, update_chat_request=update_chat_request)

Update a Chat

Updates the specified chat by setting the values of the parameters passed. Any parameters not provided will be left unchanged.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_chat200_response import GetChat200Response
from unipile.models.update_chat_request import UpdateChatRequest
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
    api_instance = unipile.MessagingApi(api_client)
    chat_id = 'chat_id_example' # str | ID of the Chat to update.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_chat_request = unipile.UpdateChatRequest() # UpdateChatRequest |  (optional)

    try:
        # Update a Chat
        api_response = api_instance.update_chat(chat_id, account_id, update_chat_request=update_chat_request)
        print("The response of MessagingApi->update_chat:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling MessagingApi->update_chat: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chat_id** | **str**| ID of the Chat to update. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_chat_request** | [**UpdateChatRequest**](UpdateChatRequest.md)|  | [optional] 

### Return type

[**GetChat200Response**](GetChat200Response.md)

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

