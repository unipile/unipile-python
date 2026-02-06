# unipile.CustomAuthApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**solve_checkpoint**](CustomAuthApi.md#solve_checkpoint) | **POST** /v2/auth/checkpoint | Solve a Checkpoint
[**start_auth_intent**](CustomAuthApi.md#start_auth_intent) | **POST** /v2/auth/intent | Start Auth Intent


# **solve_checkpoint**
> SolveCheckpoint200Response solve_checkpoint(solve_checkpoint_request)

Solve a Checkpoint

Solve the current checkpoint for the given authentication intent.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.solve_checkpoint200_response import SolveCheckpoint200Response
from unipile.models.solve_checkpoint_request import SolveCheckpointRequest
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
    api_instance = unipile.CustomAuthApi(api_client)
    solve_checkpoint_request = unipile.SolveCheckpointRequest() # SolveCheckpointRequest | 

    try:
        # Solve a Checkpoint
        api_response = api_instance.solve_checkpoint(solve_checkpoint_request)
        print("The response of CustomAuthApi->solve_checkpoint:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CustomAuthApi->solve_checkpoint: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **solve_checkpoint_request** | [**SolveCheckpointRequest**](SolveCheckpointRequest.md)|  | 

### Return type

[**SolveCheckpoint200Response**](SolveCheckpoint200Response.md)

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

# **start_auth_intent**
> SolveCheckpoint200Response start_auth_intent(start_auth_intent_request=start_auth_intent_request)

Start Auth Intent

Start an auth intent for a provider. This might require handling of checkpoints and oauth flows depending on the provider. Use <a href="https://developer.unipile.com/v2.0/reference/post_v2-auth-link">Create Auth Link</a> to let Unipile handle everything for you.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.solve_checkpoint200_response import SolveCheckpoint200Response
from unipile.models.start_auth_intent_request import StartAuthIntentRequest
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
    api_instance = unipile.CustomAuthApi(api_client)
    start_auth_intent_request = unipile.StartAuthIntentRequest() # StartAuthIntentRequest |  (optional)

    try:
        # Start Auth Intent
        api_response = api_instance.start_auth_intent(start_auth_intent_request=start_auth_intent_request)
        print("The response of CustomAuthApi->start_auth_intent:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CustomAuthApi->start_auth_intent: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **start_auth_intent_request** | [**StartAuthIntentRequest**](StartAuthIntentRequest.md)|  | [optional] 

### Return type

[**SolveCheckpoint200Response**](SolveCheckpoint200Response.md)

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

