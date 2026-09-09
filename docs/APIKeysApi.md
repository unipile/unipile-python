# unipile.APIKeysApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_api_key**](APIKeysApi.md#create_api_key) | **POST** /v2/api-keys/ | Create an API Key
[**delete_api_key**](APIKeysApi.md#delete_api_key) | **DELETE** /v2/api-keys/{api_key_id} | Delete an API Key
[**list_api_keys**](APIKeysApi.md#list_api_keys) | **GET** /v2/api-keys/ | List API Keys


# **create_api_key**
> CreateApiKey200Response create_api_key(create_api_key_request=create_api_key_request)

Create an API Key

Creates an API key that can access every account or only accounts assigned to one scope. Service API keys cannot be created through this endpoint.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_api_key200_response import CreateApiKey200Response
from unipile.models.create_api_key_request import CreateApiKeyRequest
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
    api_instance = unipile.APIKeysApi(api_client)
    create_api_key_request = unipile.CreateApiKeyRequest() # CreateApiKeyRequest |  (optional)

    try:
        # Create an API Key
        api_response = api_instance.create_api_key(create_api_key_request=create_api_key_request)
        print("The response of APIKeysApi->create_api_key:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling APIKeysApi->create_api_key: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_api_key_request** | [**CreateApiKeyRequest**](CreateApiKeyRequest.md)|  | [optional] 

### Return type

[**CreateApiKey200Response**](CreateApiKey200Response.md)

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

# **delete_api_key**
> DeleteApiKey200Response delete_api_key(api_key_id)

Delete an API Key

Deletes an account-wide or scoped API key. Service API keys cannot be deleted through this endpoint.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.delete_api_key200_response import DeleteApiKey200Response
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
    api_instance = unipile.APIKeysApi(api_client)
    api_key_id = 'api_key_id_example' # str | The ID of the Account API Key to delete.

    try:
        # Delete an API Key
        api_response = api_instance.delete_api_key(api_key_id)
        print("The response of APIKeysApi->delete_api_key:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling APIKeysApi->delete_api_key: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_key_id** | **str**| The ID of the Account API Key to delete. | 

### Return type

[**DeleteApiKey200Response**](DeleteApiKey200Response.md)

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

# **list_api_keys**
> ListApiKeys200Response list_api_keys(access=access, account_scope_id=account_scope_id, offset=offset, limit=limit)

List API Keys

Lists account-wide and scoped API keys. Service API keys are never exposed by this endpoint.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.list_api_keys200_response import ListApiKeys200Response
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
    api_instance = unipile.APIKeysApi(api_client)
    access = 'access_example' # str | Filter Account API Keys by global or Scope access. (optional)
    account_scope_id = 'account_scope_id_example' # str | Filter API Keys assigned to this Scope. (optional)
    offset = 'offset_example' # str | The number of API Keys to skip for pagination. (optional)
    limit = '20' # str | The maximum number of API Keys to return. (optional) (default to '20')

    try:
        # List API Keys
        api_response = api_instance.list_api_keys(access=access, account_scope_id=account_scope_id, offset=offset, limit=limit)
        print("The response of APIKeysApi->list_api_keys:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling APIKeysApi->list_api_keys: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **access** | **str**| Filter Account API Keys by global or Scope access. | [optional] 
 **account_scope_id** | **str**| Filter API Keys assigned to this Scope. | [optional] 
 **offset** | **str**| The number of API Keys to skip for pagination. | [optional] 
 **limit** | **str**| The maximum number of API Keys to return. | [optional] [default to &#39;20&#39;]

### Return type

[**ListApiKeys200Response**](ListApiKeys200Response.md)

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

