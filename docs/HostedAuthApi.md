# unipile.HostedAuthApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_auth_link**](HostedAuthApi.md#create_auth_link) | **POST** /v2/auth/link | Create Auth Link


# **create_auth_link**
> CreateAuthLink200Response create_auth_link(create_auth_link_request=create_auth_link_request)

Create Auth Link

Create a link to the hosted authentication wizard for the user to authenticate with the provider.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_auth_link200_response import CreateAuthLink200Response
from unipile.models.create_auth_link_request import CreateAuthLinkRequest
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
    api_instance = unipile.HostedAuthApi(api_client)
    create_auth_link_request = unipile.CreateAuthLinkRequest() # CreateAuthLinkRequest |  (optional)

    try:
        # Create Auth Link
        api_response = api_instance.create_auth_link(create_auth_link_request=create_auth_link_request)
        print("The response of HostedAuthApi->create_auth_link:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling HostedAuthApi->create_auth_link: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_auth_link_request** | [**CreateAuthLinkRequest**](CreateAuthLinkRequest.md)|  | [optional] 

### Return type

[**CreateAuthLink200Response**](CreateAuthLink200Response.md)

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

