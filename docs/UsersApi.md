# unipile.UsersApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**accept_relation_request**](UsersApi.md#accept_relation_request) | **POST** /v2/{account_id}/users/me/relation-requests/{request_id}/accept | Accept a Relation request
[**cancel_relation_request**](UsersApi.md#cancel_relation_request) | **POST** /v2/{account_id}/users/me/relation-requests/{request_id}/cancel | Cancel or Refuse a Relation / Follow request
[**create_relation_request**](UsersApi.md#create_relation_request) | **POST** /v2/{account_id}/users/me/relation-requests | Send a Relation request
[**delete_relation**](UsersApi.md#delete_relation) | **DELETE** /v2/{account_id}/users/me/relations/{user_id} | Delete a Relation
[**follow_user**](UsersApi.md#follow_user) | **POST** /v2/{account_id}/users/me/follow/{user_id} | Follow a User
[**get_posts_list**](UsersApi.md#get_posts_list) | **GET** /v2/{account_id}/users/{user_id}/posts | List all User&#39;s Posts
[**get_relation_requests_list**](UsersApi.md#get_relation_requests_list) | **GET** /v2/{account_id}/users/me/relation-requests | List all pending Relation / Follow requests
[**get_user_profile**](UsersApi.md#get_user_profile) | **GET** /v2/{account_id}/users/{user_id} | Get a User Profile
[**get_user_relations**](UsersApi.md#get_user_relations) | **GET** /v2/{account_id}/users/{user_id}/relations | List Relations of a User
[**list_user_followers**](UsersApi.md#list_user_followers) | **GET** /v2/{account_id}/users/{user_id}/followers | List Followers of a User
[**list_user_following**](UsersApi.md#list_user_following) | **GET** /v2/{account_id}/users/{user_id}/following | List Following of a User
[**unfollow_user**](UsersApi.md#unfollow_user) | **POST** /v2/{account_id}/users/me/unfollow/{user_id} | Unfollow a User
[**update_user_profile**](UsersApi.md#update_user_profile) | **PATCH** /v2/{account_id}/users/{user_id} | Update a User Profile
[**visit_user_profile**](UsersApi.md#visit_user_profile) | **POST** /v2/{account_id}/users/visit-profile | Report a Profile Visit


# **accept_relation_request**
> AcceptRelationRequest200Response accept_relation_request(request_id, account_id)

Accept a Relation request

Accepts a received relation request from another user. Trying to accept a sent relation request will fail.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.accept_relation_request200_response import AcceptRelationRequest200Response
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
    api_instance = unipile.UsersApi(api_client)
    request_id = 'request_id_example' # str | The ID of the Relation / Follow request.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Accept a Relation request
        api_response = api_instance.accept_relation_request(request_id, account_id)
        print("The response of UsersApi->accept_relation_request:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->accept_relation_request: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request_id** | **str**| The ID of the Relation / Follow request. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**AcceptRelationRequest200Response**](AcceptRelationRequest200Response.md)

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

# **cancel_relation_request**
> CancelRelationRequest200Response cancel_relation_request(request_id, account_id)

Cancel or Refuse a Relation / Follow request

Cancels the relation / follow request if sent by the owner of the account to another user. Refuses the relation / follow request if received by the owner of the account from another user.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.cancel_relation_request200_response import CancelRelationRequest200Response
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
    api_instance = unipile.UsersApi(api_client)
    request_id = 'request_id_example' # str | The ID of the Relation / Follow request.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Cancel or Refuse a Relation / Follow request
        api_response = api_instance.cancel_relation_request(request_id, account_id)
        print("The response of UsersApi->cancel_relation_request:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->cancel_relation_request: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request_id** | **str**| The ID of the Relation / Follow request. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**CancelRelationRequest200Response**](CancelRelationRequest200Response.md)

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

# **create_relation_request**
> LinkedInRelationRequest create_relation_request(account_id, create_relation_request_request)

Send a Relation request

Sends a bi-directional relation request to a user. Trying to send a relation request to an existing relation will fail. For uni-directional relations, use `Follow User` instead.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_relation_request_request import CreateRelationRequestRequest
from unipile.models.linked_in_relation_request import LinkedInRelationRequest
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
    api_instance = unipile.UsersApi(api_client)
    account_id = 'account_id_example' # str | 
    create_relation_request_request = unipile.CreateRelationRequestRequest() # CreateRelationRequestRequest | 

    try:
        # Send a Relation request
        api_response = api_instance.create_relation_request(account_id, create_relation_request_request)
        print("The response of UsersApi->create_relation_request:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->create_relation_request: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**|  | 
 **create_relation_request_request** | [**CreateRelationRequestRequest**](CreateRelationRequestRequest.md)|  | 

### Return type

[**LinkedInRelationRequest**](LinkedInRelationRequest.md)

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

# **delete_relation**
> delete_relation(user_id, account_id)

Delete a Relation

Deletes a bi-directional relation with another user. For uni-directional relations, use `Unfollow User` instead.

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
    api_instance = unipile.UsersApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to delete the relation with.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Delete a Relation
        api_instance.delete_relation(user_id, account_id)
    except Exception as e:
        print("Exception when calling UsersApi->delete_relation: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| The ID of the User to delete the relation with. | 
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

# **follow_user**
> FollowUser200Response follow_user(user_id, account_id)

Follow a User

Follows a user. Trying to follow an already followed User will fail. For bi-directional relations, use `Send Relation Request` instead. If the User has a private profile, this will create a Follow Request.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.follow_user200_response import FollowUser200Response
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
    api_instance = unipile.UsersApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to follow.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Follow a User
        api_response = api_instance.follow_user(user_id, account_id)
        print("The response of UsersApi->follow_user:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->follow_user: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| The ID of the User to follow. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**FollowUser200Response**](FollowUser200Response.md)

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
    api_instance = unipile.UsersApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to retrieve posts from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all User's Posts
        api_response = api_instance.get_posts_list(user_id, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of UsersApi->get_posts_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->get_posts_list: %s\n" % e)
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

# **get_relation_requests_list**
> GetRelationRequestsList200Response get_relation_requests_list(type, account_id, offset=offset, limit=limit, cursor=cursor)

List all pending Relation / Follow requests

Returns a list of pending relation / follow requests that have been sent or received by the owner of the account.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_relation_requests_list200_response import GetRelationRequestsList200Response
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
    api_instance = unipile.UsersApi(api_client)
    type = 'type_example' # str | Filter to returns only the given type of Relation / Follow request.         - `sent` is the requests sent by the current user.         - `received` is the requests received by the current user.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List all pending Relation / Follow requests
        api_response = api_instance.get_relation_requests_list(type, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of UsersApi->get_relation_requests_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->get_relation_requests_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type** | **str**| Filter to returns only the given type of Relation / Follow request.         - &#x60;sent&#x60; is the requests sent by the current user.         - &#x60;received&#x60; is the requests received by the current user. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetRelationRequestsList200Response**](GetRelationRequestsList200Response.md)

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

# **get_user_profile**
> GetUserProfile200Response get_user_profile(user_id, account_id, with_sections=with_sections, variant=variant)

Get a User Profile

Retrieves the specified User profile. Use `me` as `user_id` to specify the owner of the connected account.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_user_profile200_response import GetUserProfile200Response
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
    api_instance = unipile.UsersApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to retrieve.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    with_sections = None # List |  (optional)
    variant = 'variant_example' # str |  (optional)

    try:
        # Get a User Profile
        api_response = api_instance.get_user_profile(user_id, account_id, with_sections=with_sections, variant=variant)
        print("The response of UsersApi->get_user_profile:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->get_user_profile: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| The ID of the User to retrieve. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **with_sections** | [**List**](.md)|  | [optional] 
 **variant** | [**str**](.md)|  | [optional] 

### Return type

[**GetUserProfile200Response**](GetUserProfile200Response.md)

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

# **get_user_relations**
> GetUserRelations200Response get_user_relations(user_id, account_id, search=search, offset=offset, limit=limit, cursor=cursor)

List Relations of a User

Returns a list of bi-directional relations for the specified User. Use `me` as `user_id` to specify the owner of the connected account.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_user_relations200_response import GetUserRelations200Response
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
    api_instance = unipile.UsersApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to get the relations from.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    search = 'search_example' # str | Any text input to filter out results (if supported by the provider). (optional)
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List Relations of a User
        api_response = api_instance.get_user_relations(user_id, account_id, search=search, offset=offset, limit=limit, cursor=cursor)
        print("The response of UsersApi->get_user_relations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->get_user_relations: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| The ID of the User to get the relations from. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **search** | **str**| Any text input to filter out results (if supported by the provider). | [optional] 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**GetUserRelations200Response**](GetUserRelations200Response.md)

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

# **list_user_followers**
> ListUserFollowers200Response list_user_followers(user_id, account_id, offset=offset, limit=limit, cursor=cursor)

List Followers of a User

Returns a list of followers of the specified User. Set `me` as `user_id` to specify the owner of the connected account.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.list_user_followers200_response import ListUserFollowers200Response
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
    api_instance = unipile.UsersApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to get the followers from. Use `me` to get the followers of the account owner.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List Followers of a User
        api_response = api_instance.list_user_followers(user_id, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of UsersApi->list_user_followers:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->list_user_followers: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| The ID of the User to get the followers from. Use &#x60;me&#x60; to get the followers of the account owner. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**ListUserFollowers200Response**](ListUserFollowers200Response.md)

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

# **list_user_following**
> ListUserFollowers200Response list_user_following(user_id, account_id, offset=offset, limit=limit, cursor=cursor)

List Following of a User

Returns a list of Users followed by the specified User. Set `me` as `user_id` to specify the owner of the connected account.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.list_user_followers200_response import ListUserFollowers200Response
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
    api_instance = unipile.UsersApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to get the followed users from. Use `me` to get the followed users of the account owner.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)

    try:
        # List Following of a User
        api_response = api_instance.list_user_following(user_id, account_id, offset=offset, limit=limit, cursor=cursor)
        print("The response of UsersApi->list_user_following:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->list_user_following: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| The ID of the User to get the followed users from. Use &#x60;me&#x60; to get the followed users of the account owner. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 

### Return type

[**ListUserFollowers200Response**](ListUserFollowers200Response.md)

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

# **unfollow_user**
> UnfollowUser200Response unfollow_user(user_id, account_id)

Unfollow a User

Unfollows a user. Trying to unfollow a not followed User will fail.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.unfollow_user200_response import UnfollowUser200Response
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
    api_instance = unipile.UsersApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to unfollow.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Unfollow a User
        api_response = api_instance.unfollow_user(user_id, account_id)
        print("The response of UsersApi->unfollow_user:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->unfollow_user: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| The ID of the User to unfollow. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**UnfollowUser200Response**](UnfollowUser200Response.md)

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

# **update_user_profile**
> UpdateUserProfile200Response update_user_profile(user_id, account_id, update_user_profile_request=update_user_profile_request)

Update a User Profile

Updates the specified User profile. Use `me` as `user_id` to update the account owner profile.
      <br/>
      Multipart supported, refer to <a href="https://developer.unipile.com/v2.0/reference/api-usage#sending-files">Sending Files</a>.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.update_user_profile200_response import UpdateUserProfile200Response
from unipile.models.update_user_profile_request import UpdateUserProfileRequest
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
    api_instance = unipile.UsersApi(api_client)
    user_id = 'user_id_example' # str | The ID of the User to update. Use `me` to update the account owner profile.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_user_profile_request = unipile.UpdateUserProfileRequest() # UpdateUserProfileRequest |  (optional)

    try:
        # Update a User Profile
        api_response = api_instance.update_user_profile(user_id, account_id, update_user_profile_request=update_user_profile_request)
        print("The response of UsersApi->update_user_profile:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->update_user_profile: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_id** | **str**| The ID of the User to update. Use &#x60;me&#x60; to update the account owner profile. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_user_profile_request** | [**UpdateUserProfileRequest**](UpdateUserProfileRequest.md)|  | [optional] 

### Return type

[**UpdateUserProfile200Response**](UpdateUserProfile200Response.md)

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

# **visit_user_profile**
> VisitUserProfile200Response visit_user_profile(token, account_id)

Report a Profile Visit

Report to the provider that you have visited a given user profile. This can be used to simulate engagement and activity.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.visit_user_profile200_response import VisitUserProfile200Response
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
    api_instance = unipile.UsersApi(api_client)
    token = 'token_example' # str | The `notify_visit_token` field that you may get from a profile result, depending on whether the provider supports it.
    account_id = 'account_id_example' # str | 

    try:
        # Report a Profile Visit
        api_response = api_instance.visit_user_profile(token, account_id)
        print("The response of UsersApi->visit_user_profile:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling UsersApi->visit_user_profile: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **str**| The &#x60;notify_visit_token&#x60; field that you may get from a profile result, depending on whether the provider supports it. | 
 **account_id** | **str**|  | 

### Return type

[**VisitUserProfile200Response**](VisitUserProfile200Response.md)

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

