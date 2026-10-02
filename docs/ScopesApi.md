# unipile.ScopesApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_scope**](ScopesApi.md#create_scope) | **POST** /v2/scopes/ | Create a Scope
[**delete_scope**](ScopesApi.md#delete_scope) | **DELETE** /v2/scopes/{scope_id} | Delete a Scope
[**get_scope**](ScopesApi.md#get_scope) | **GET** /v2/scopes/{scope_id} | Get a Scope
[**list_scopes**](ScopesApi.md#list_scopes) | **GET** /v2/scopes/ | List Scopes
[**update_scope**](ScopesApi.md#update_scope) | **PATCH** /v2/scopes/{scope_id} | Update a Scope


# **create_scope**
> CreateScope200Response create_scope(create_scope_request)

Create a Scope

Creates a Scope in the authenticated Application. A Scope is an isolation boundary used to restrict Account API Keys to the Accounts assigned to it.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_scope200_response import CreateScope200Response
from unipile.models.create_scope_request import CreateScopeRequest
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
    api_instance = unipile.ScopesApi(api_client)
    create_scope_request = unipile.CreateScopeRequest() # CreateScopeRequest | 

    try:
        # Create a Scope
        api_response = api_instance.create_scope(create_scope_request)
        print("The response of ScopesApi->create_scope:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ScopesApi->create_scope: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_scope_request** | [**CreateScopeRequest**](CreateScopeRequest.md)|  | 

### Return type

[**CreateScope200Response**](CreateScope200Response.md)

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

# **delete_scope**
> DeleteScope200Response delete_scope(scope_id)

Delete a Scope

Deletes a Scope from the authenticated Application. The Scope must not contain any Accounts or API Keys, including expired API Keys.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.delete_scope200_response import DeleteScope200Response
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
    api_instance = unipile.ScopesApi(api_client)
    scope_id = 'scope_id_example' # str | The ID of the Scope to delete.

    try:
        # Delete a Scope
        api_response = api_instance.delete_scope(scope_id)
        print("The response of ScopesApi->delete_scope:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ScopesApi->delete_scope: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **scope_id** | **str**| The ID of the Scope to delete. | 

### Return type

[**DeleteScope200Response**](DeleteScope200Response.md)

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

# **get_scope**
> CreateScope200Response get_scope(scope_id)

Get a Scope

Returns a Scope from the authenticated Application, including its status and the number of Accounts and API Keys assigned to it.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_scope200_response import CreateScope200Response
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
    api_instance = unipile.ScopesApi(api_client)
    scope_id = 'scope_id_example' # str | The ID of the Scope to retrieve.

    try:
        # Get a Scope
        api_response = api_instance.get_scope(scope_id)
        print("The response of ScopesApi->get_scope:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ScopesApi->get_scope: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **scope_id** | **str**| The ID of the Scope to retrieve. | 

### Return type

[**CreateScope200Response**](CreateScope200Response.md)

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

# **list_scopes**
> ListScopes200Response list_scopes(offset=offset, limit=limit, status=status, search=search)

List Scopes

Returns the Scopes created in the authenticated Application, including their status and the number of Accounts and API Keys assigned to each Scope.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.list_scopes200_response import ListScopes200Response
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
    api_instance = unipile.ScopesApi(api_client)
    offset = 'offset_example' # str | The number of Scopes to skip for pagination. (optional)
    limit = '20' # str | The maximum number of Scopes to return. (optional) (default to '20')
    status = 'status_example' # str | The status of the Scope. A disabled scope blocks its scoped API keys and authentication flows until it is enabled again. (optional)
    search = 'search_example' # str | Filter scopes by name or reference. (optional)

    try:
        # List Scopes
        api_response = api_instance.list_scopes(offset=offset, limit=limit, status=status, search=search)
        print("The response of ScopesApi->list_scopes:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ScopesApi->list_scopes: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **offset** | **str**| The number of Scopes to skip for pagination. | [optional] 
 **limit** | **str**| The maximum number of Scopes to return. | [optional] [default to &#39;20&#39;]
 **status** | **str**| The status of the Scope. A disabled scope blocks its scoped API keys and authentication flows until it is enabled again. | [optional] 
 **search** | **str**| Filter scopes by name or reference. | [optional] 

### Return type

[**ListScopes200Response**](ListScopes200Response.md)

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

# **update_scope**
> CreateScope200Response update_scope(scope_id, update_scope_request=update_scope_request)

Update a Scope

Updates the name, unique reference, or status of a Scope. Disabling a Scope blocks its Account API Keys and authentication flows until it is enabled again.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_scope200_response import CreateScope200Response
from unipile.models.update_scope_request import UpdateScopeRequest
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
    api_instance = unipile.ScopesApi(api_client)
    scope_id = 'scope_id_example' # str | The ID of the Scope to update.
    update_scope_request = unipile.UpdateScopeRequest() # UpdateScopeRequest |  (optional)

    try:
        # Update a Scope
        api_response = api_instance.update_scope(scope_id, update_scope_request=update_scope_request)
        print("The response of ScopesApi->update_scope:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ScopesApi->update_scope: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **scope_id** | **str**| The ID of the Scope to update. | 
 **update_scope_request** | [**UpdateScopeRequest**](UpdateScopeRequest.md)|  | [optional] 

### Return type

[**CreateScope200Response**](CreateScope200Response.md)

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

