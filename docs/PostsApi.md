# unipile.PostsApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**add_post_comment**](PostsApi.md#add_post_comment) | **POST** /v2/{account_id}/posts/{post_id}/comments | Add Comment to a Post
[**add_post_comment_reaction**](PostsApi.md#add_post_comment_reaction) | **POST** /v2/{account_id}/posts/{post_id}/comments/{comment_id}/reactions | Add Reaction to a Comment
[**add_post_reaction**](PostsApi.md#add_post_reaction) | **POST** /v2/{account_id}/posts/{post_id}/reactions | Add Reaction to a Post
[**create_post**](PostsApi.md#create_post) | **POST** /v2/{account_id}/posts | Create a Post
[**delete_post**](PostsApi.md#delete_post) | **DELETE** /v2/{account_id}/posts/{post_id} | Delete a Post
[**delete_post_comment**](PostsApi.md#delete_post_comment) | **DELETE** /v2/{account_id}/posts/{post_id}/comments/{comment_id} | Delete Comment from a Post
[**get_post**](PostsApi.md#get_post) | **GET** /v2/{account_id}/posts/{post_id} | Get a Post
[**get_post_comment_reactions_list**](PostsApi.md#get_post_comment_reactions_list) | **GET** /v2/{account_id}/posts/{post_id}/comments/{comment_id}/reactions | List all Comment&#39;s Reactions
[**get_post_comment_replies_list**](PostsApi.md#get_post_comment_replies_list) | **GET** /v2/{account_id}/posts/{post_id}/comments/{comment_id}/replies | List all Comment&#39;s Replies
[**get_post_comments_list**](PostsApi.md#get_post_comments_list) | **GET** /v2/{account_id}/posts/{post_id}/comments | List all Post&#39;s Comments
[**get_post_reactions_list**](PostsApi.md#get_post_reactions_list) | **GET** /v2/{account_id}/posts/{post_id}/reactions | List all Post&#39;s Reactions
[**get_posts_list**](PostsApi.md#get_posts_list) | **GET** /v2/{account_id}/users/{user_id}/posts | List all User&#39;s Posts
[**get_user_comments_list**](PostsApi.md#get_user_comments_list) | **GET** /v2/{account_id}/users/{user_id}/comments | List all User Comments
[**get_user_reactions_list**](PostsApi.md#get_user_reactions_list) | **GET** /v2/{account_id}/users/{user_id}/reactions | List all User Reactions
[**remove_post_comment_reaction**](PostsApi.md#remove_post_comment_reaction) | **DELETE** /v2/{account_id}/posts/{post_id}/comments/{comment_id}/reactions | Remove Reaction from a Comment
[**remove_post_reaction**](PostsApi.md#remove_post_reaction) | **DELETE** /v2/{account_id}/posts/{post_id}/reactions | Remove Reaction from a Post
[**reply_to_comment**](PostsApi.md#reply_to_comment) | **POST** /v2/{account_id}/posts/{post_id}/comments/{comment_id} | Reply to a Comment
[**update_post**](PostsApi.md#update_post) | **PATCH** /v2/{account_id}/posts/{post_id} | Update a Post
[**update_post_comment**](PostsApi.md#update_post_comment) | **PATCH** /v2/{account_id}/posts/{post_id}/comments/{comment_id} | Update a Comment


# **add_post_comment**
> GetPostCommentsList200ResponseDataInner add_post_comment(post_id, account_id, add_post_comment_request)

Add Comment to a Post

Adds a comment to a post.
      <br/>
      Multipart supported, refer to <a href="https://developer.unipile.com/v2.0/reference/api-usage#sending-files">Sending Files</a>.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.add_post_comment_request import AddPostCommentRequest
from unipile.models.get_post_comments_list200_response_data_inner import GetPostCommentsList200ResponseDataInner
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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post to add the comment to.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    add_post_comment_request = unipile.AddPostCommentRequest() # AddPostCommentRequest | 

    try:
        # Add Comment to a Post
        api_response = api_instance.add_post_comment(post_id, account_id, add_post_comment_request)
        print("The response of PostsApi->add_post_comment:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->add_post_comment: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post to add the comment to. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **add_post_comment_request** | [**AddPostCommentRequest**](AddPostCommentRequest.md)|  | 

### Return type

[**GetPostCommentsList200ResponseDataInner**](GetPostCommentsList200ResponseDataInner.md)

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

# **add_post_comment_reaction**
> AddPostCommentReaction200Response add_post_comment_reaction(post_id, comment_id, account_id, add_post_comment_reaction_request)

Add Reaction to a Comment

Adds a reaction to a post.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.add_post_comment_reaction200_response import AddPostCommentReaction200Response
from unipile.models.add_post_comment_reaction_request import AddPostCommentReactionRequest
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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post where the comment is.
    comment_id = 'comment_id_example' # str | The ID of the Comment to add the reaction to.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    add_post_comment_reaction_request = unipile.AddPostCommentReactionRequest() # AddPostCommentReactionRequest | 

    try:
        # Add Reaction to a Comment
        api_response = api_instance.add_post_comment_reaction(post_id, comment_id, account_id, add_post_comment_reaction_request)
        print("The response of PostsApi->add_post_comment_reaction:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->add_post_comment_reaction: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post where the comment is. | 
 **comment_id** | **str**| The ID of the Comment to add the reaction to. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **add_post_comment_reaction_request** | [**AddPostCommentReactionRequest**](AddPostCommentReactionRequest.md)|  | 

### Return type

[**AddPostCommentReaction200Response**](AddPostCommentReaction200Response.md)

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

# **add_post_reaction**
> AddPostReaction200Response add_post_reaction(post_id, account_id, add_post_reaction_request)

Add Reaction to a Post

Adds a reaction to a post.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.add_post_reaction200_response import AddPostReaction200Response
from unipile.models.add_post_reaction_request import AddPostReactionRequest
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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post to add the reaction to.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    add_post_reaction_request = unipile.AddPostReactionRequest() # AddPostReactionRequest | 

    try:
        # Add Reaction to a Post
        api_response = api_instance.add_post_reaction(post_id, account_id, add_post_reaction_request)
        print("The response of PostsApi->add_post_reaction:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->add_post_reaction: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post to add the reaction to. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **add_post_reaction_request** | [**AddPostReactionRequest**](AddPostReactionRequest.md)|  | 

### Return type

[**AddPostReaction200Response**](AddPostReaction200Response.md)

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

# **create_post**
> GetPost200Response create_post(account_id, create_post_request)

Create a Post

Creates a new post.
      <br/>
      Multipart supported, refer to <a href="https://developer.unipile.com/v2.0/reference/api-usage#sending-files">Sending Files</a>.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_post_request import CreatePostRequest
from unipile.models.get_post200_response import GetPost200Response
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
    api_instance = unipile.PostsApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_post_request = unipile.CreatePostRequest() # CreatePostRequest | 

    try:
        # Create a Post
        api_response = api_instance.create_post(account_id, create_post_request)
        print("The response of PostsApi->create_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->create_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_post_request** | [**CreatePostRequest**](CreatePostRequest.md)|  | 

### Return type

[**GetPost200Response**](GetPost200Response.md)

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

# **delete_post**
> delete_post(post_id, account_id)

Delete a Post

Deletes a post created by the owner of the account. Trying to delete a post created by another user will fail.

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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post to delete.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Delete a Post
        api_instance.delete_post(post_id, account_id)
    except Exception as e:
        print("Exception when calling PostsApi->delete_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post to delete. | 
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

# **delete_post_comment**
> delete_post_comment(post_id, comment_id, account_id)

Delete Comment from a Post

Deletes a comment of the account's owner from a post. Trying to delete a comment from another user will fail.

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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post where the comment is.
    comment_id = 'comment_id_example' # str | The ID of the Comment to delete.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Delete Comment from a Post
        api_instance.delete_post_comment(post_id, comment_id, account_id)
    except Exception as e:
        print("Exception when calling PostsApi->delete_post_comment: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post where the comment is. | 
 **comment_id** | **str**| The ID of the Comment to delete. | 
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

# **get_post**
> GetPost200Response get_post(post_id, account_id)

Get a Post

Retrieves the specified post.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_post200_response import GetPost200Response
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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post to retrieve.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Post
        api_response = api_instance.get_post(post_id, account_id)
        print("The response of PostsApi->get_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->get_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post to retrieve. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetPost200Response**](GetPost200Response.md)

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

# **get_post_comment_reactions_list**
> GetMessageReactionsList200Response get_post_comment_reactions_list(post_id, comment_id, account_id, offset=offset, limit=limit, cursor=cursor)

List all Comment's Reactions

Returns the list of reactions made to a comment. Reaction counts are given with the Comment object. This is useful to show a detailed list of all reactions and their author.

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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post where the comment is.
    comment_id = 'comment_id_example' # str | The ID of the Comment to retrieve reactions from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all Comment's Reactions
        api_response = api_instance.get_post_comment_reactions_list(post_id, comment_id, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of PostsApi->get_post_comment_reactions_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->get_post_comment_reactions_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post where the comment is. | 
 **comment_id** | **str**| The ID of the Comment to retrieve reactions from. | 
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

# **get_post_comment_replies_list**
> GetPostCommentsList200Response get_post_comment_replies_list(post_id, comment_id, account_id, offset=offset, limit=limit, cursor=cursor)

List all Comment's Replies

Returns the list of replies to a comment. The replies are returned sorted by their creation date, with the most recent appearing first.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_post_comments_list200_response import GetPostCommentsList200Response
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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post where the comment is.
    comment_id = 'comment_id_example' # str | The ID of the Comment to retrieve replies from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all Comment's Replies
        api_response = api_instance.get_post_comment_replies_list(post_id, comment_id, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of PostsApi->get_post_comment_replies_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->get_post_comment_replies_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post where the comment is. | 
 **comment_id** | **str**| The ID of the Comment to retrieve replies from. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetPostCommentsList200Response**](GetPostCommentsList200Response.md)

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

# **get_post_comments_list**
> GetPostCommentsList200Response get_post_comments_list(post_id, account_id, offset=offset, limit=limit, cursor=cursor, sort_by=sort_by)

List all Post's Comments

Returns a list of post comments. The comments are returned sorted by their creation date, with the most recent appearing first.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_post_comments_list200_response import GetPostCommentsList200Response
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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post to retrieve comments from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)
    sort_by = MOST_RECENT # str | Sort criterion for the posts list: MOST_RECENT (most recent first) or MOST_RELEVANT (most relevant first). (optional) (default to MOST_RECENT)

    try:
        # List all Post's Comments
        api_response = api_instance.get_post_comments_list(post_id, account_id, offset=offset, limit=limit, cursor=cursor, sort_by=sort_by)
        print("The response of PostsApi->get_post_comments_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->get_post_comments_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post to retrieve comments from. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 
 **sort_by** | **str**| Sort criterion for the posts list: MOST_RECENT (most recent first) or MOST_RELEVANT (most relevant first). | [optional] [default to MOST_RECENT]

### Return type

[**GetPostCommentsList200Response**](GetPostCommentsList200Response.md)

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

# **get_post_reactions_list**
> GetMessageReactionsList200Response get_post_reactions_list(post_id, account_id, offset=offset, limit=limit, cursor=cursor)

List all Post's Reactions

Returns the list of reactions made to a post. Reaction counts are given with the Post object. This is useful to show a detailed list of all reactions and their author. LIMITATIONS: On Instagram, the list is always limited to a maximum of 100 reactions.

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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post to retrieve reactions from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all Post's Reactions
        api_response = api_instance.get_post_reactions_list(post_id, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of PostsApi->get_post_reactions_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->get_post_reactions_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post to retrieve reactions from. | 
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

# **get_posts_list**
> GetPostsList200Response get_posts_list(user_id, account_id, offset=offset, limit=limit, cursor=cursor)

List all User's Posts

Returns a list of posts created or shared by a user. Use `me` as `user_id` to specify the owner of the connected account.

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
    api_instance = unipile.PostsApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to retrieve posts from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all User's Posts
        api_response = api_instance.get_posts_list(user_id, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of PostsApi->get_posts_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->get_posts_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| The ID of the User to retrieve posts from. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

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

# **get_user_comments_list**
> GetUserCommentsList200Response get_user_comments_list(user_id, account_id, offset=offset, limit=limit, cursor=cursor)

List all User Comments

Returns the list of comments made by a user to posts. Use `me` as `user_id` to specify the owner of the connected account.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_user_comments_list200_response import GetUserCommentsList200Response
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
    api_instance = unipile.PostsApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to retrieve the comments from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all User Comments
        api_response = api_instance.get_user_comments_list(user_id, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of PostsApi->get_user_comments_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->get_user_comments_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| The ID of the User to retrieve the comments from. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetUserCommentsList200Response**](GetUserCommentsList200Response.md)

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

# **get_user_reactions_list**
> GetUserReactionsList200Response get_user_reactions_list(user_id, account_id, offset=offset, limit=limit, cursor=cursor)

List all User Reactions

Returns the list of reactions made by a user to posts. Use `me` as `user_id` to specify the owner of the connected account.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_user_reactions_list200_response import GetUserReactionsList200Response
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
    api_instance = unipile.PostsApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to retrieve the reactions from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all User Reactions
        api_response = api_instance.get_user_reactions_list(user_id, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of PostsApi->get_user_reactions_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->get_user_reactions_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| The ID of the User to retrieve the reactions from. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetUserReactionsList200Response**](GetUserReactionsList200Response.md)

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

# **remove_post_comment_reaction**
> RemovePostCommentReaction200Response remove_post_comment_reaction(post_id, comment_id, account_id, remove_post_comment_reaction_request)

Remove Reaction from a Comment

Removes a reaction of the account's owner from a comment. Trying to remove a reaction from another user will fail.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.remove_post_comment_reaction200_response import RemovePostCommentReaction200Response
from unipile.models.remove_post_comment_reaction_request import RemovePostCommentReactionRequest
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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post where the comment is.
    comment_id = 'comment_id_example' # str | The ID of the Comment where the reaction is.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    remove_post_comment_reaction_request = unipile.RemovePostCommentReactionRequest() # RemovePostCommentReactionRequest | 

    try:
        # Remove Reaction from a Comment
        api_response = api_instance.remove_post_comment_reaction(post_id, comment_id, account_id, remove_post_comment_reaction_request)
        print("The response of PostsApi->remove_post_comment_reaction:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->remove_post_comment_reaction: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post where the comment is. | 
 **comment_id** | **str**| The ID of the Comment where the reaction is. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **remove_post_comment_reaction_request** | [**RemovePostCommentReactionRequest**](RemovePostCommentReactionRequest.md)|  | 

### Return type

[**RemovePostCommentReaction200Response**](RemovePostCommentReaction200Response.md)

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

# **remove_post_reaction**
> RemovePostReaction200Response remove_post_reaction(post_id, account_id, remove_post_reaction_request)

Remove Reaction from a Post

Removes a reaction from a post.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.remove_post_reaction200_response import RemovePostReaction200Response
from unipile.models.remove_post_reaction_request import RemovePostReactionRequest
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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post where the reaction is.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    remove_post_reaction_request = unipile.RemovePostReactionRequest() # RemovePostReactionRequest | 

    try:
        # Remove Reaction from a Post
        api_response = api_instance.remove_post_reaction(post_id, account_id, remove_post_reaction_request)
        print("The response of PostsApi->remove_post_reaction:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->remove_post_reaction: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post where the reaction is. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **remove_post_reaction_request** | [**RemovePostReactionRequest**](RemovePostReactionRequest.md)|  | 

### Return type

[**RemovePostReaction200Response**](RemovePostReaction200Response.md)

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

# **reply_to_comment**
> GetPostCommentsList200ResponseDataInner reply_to_comment(post_id, comment_id, account_id, add_post_comment_request)

Reply to a Comment

Replies to a particular comment.
      <br/>
      Multipart supported, refer to <a href="https://developer.unipile.com/v2.0/reference/api-usage#sending-files">Sending Files</a>.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.add_post_comment_request import AddPostCommentRequest
from unipile.models.get_post_comments_list200_response_data_inner import GetPostCommentsList200ResponseDataInner
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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post to add the comment to.
    comment_id = 'comment_id_example' # str | The ID of the Comment to reply to.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    add_post_comment_request = unipile.AddPostCommentRequest() # AddPostCommentRequest | 

    try:
        # Reply to a Comment
        api_response = api_instance.reply_to_comment(post_id, comment_id, account_id, add_post_comment_request)
        print("The response of PostsApi->reply_to_comment:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->reply_to_comment: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post to add the comment to. | 
 **comment_id** | **str**| The ID of the Comment to reply to. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **add_post_comment_request** | [**AddPostCommentRequest**](AddPostCommentRequest.md)|  | 

### Return type

[**GetPostCommentsList200ResponseDataInner**](GetPostCommentsList200ResponseDataInner.md)

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

# **update_post**
> GetPost200Response update_post(post_id, account_id, update_post_request=update_post_request)

Update a Post

Updates an existing post.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_post200_response import GetPost200Response
from unipile.models.update_post_request import UpdatePostRequest
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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post to update.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_post_request = unipile.UpdatePostRequest() # UpdatePostRequest |  (optional)

    try:
        # Update a Post
        api_response = api_instance.update_post(post_id, account_id, update_post_request=update_post_request)
        print("The response of PostsApi->update_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->update_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post to update. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_post_request** | [**UpdatePostRequest**](UpdatePostRequest.md)|  | [optional] 

### Return type

[**GetPost200Response**](GetPost200Response.md)

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

# **update_post_comment**
> GetPostCommentsList200ResponseDataInner update_post_comment(post_id, comment_id, account_id, update_post_comment_request)

Update a Comment

Updates an existing comment.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_post_comments_list200_response_data_inner import GetPostCommentsList200ResponseDataInner
from unipile.models.update_post_comment_request import UpdatePostCommentRequest
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
    api_instance = unipile.PostsApi(api_client)
    post_id = 'post_id_example' # str | The ID of the Post where the comment is.
    comment_id = 'comment_id_example' # str | The ID of the Comment to update.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_post_comment_request = unipile.UpdatePostCommentRequest() # UpdatePostCommentRequest | 

    try:
        # Update a Comment
        api_response = api_instance.update_post_comment(post_id, comment_id, account_id, update_post_comment_request)
        print("The response of PostsApi->update_post_comment:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PostsApi->update_post_comment: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **post_id** | **str**| The ID of the Post where the comment is. | 
 **comment_id** | **str**| The ID of the Comment to update. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_post_comment_request** | [**UpdatePostCommentRequest**](UpdatePostCommentRequest.md)|  | 

### Return type

[**GetPostCommentsList200ResponseDataInner**](GetPostCommentsList200ResponseDataInner.md)

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

