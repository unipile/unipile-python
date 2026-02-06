# unipile.WebhooksApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_webhook_endpoint**](WebhooksApi.md#create_webhook_endpoint) | **POST** /v2/webhooks/endpoints/ | Create a Webhook Endpoint
[**delete_webhook_endpoint**](WebhooksApi.md#delete_webhook_endpoint) | **DELETE** /v2/webhooks/endpoints/{id} | Delete a Webhook Endpoint
[**get_webhook_endpoint**](WebhooksApi.md#get_webhook_endpoint) | **GET** /v2/webhooks/endpoints/{id} | Get a Webhook Endpoint
[**list_webhook_conversations**](WebhooksApi.md#list_webhook_conversations) | **GET** /v2/webhooks/conversations/ | List all Webhook Conversations
[**list_webhook_endpoints**](WebhooksApi.md#list_webhook_endpoints) | **GET** /v2/webhooks/endpoints/ | List all Webhook Endpoints
[**update_webhook_endpoint**](WebhooksApi.md#update_webhook_endpoint) | **PATCH** /v2/webhooks/endpoints/{id} | Update a Webhook Endpoint


# **create_webhook_endpoint**
> CreateWebhookEndpoint200Response create_webhook_endpoint(create_webhook_endpoint_request)

Create a Webhook Endpoint

Creates a new webhook endpoint.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_webhook_endpoint200_response import CreateWebhookEndpoint200Response
from unipile.models.create_webhook_endpoint_request import CreateWebhookEndpointRequest
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
    api_instance = unipile.WebhooksApi(api_client)
    create_webhook_endpoint_request = unipile.CreateWebhookEndpointRequest() # CreateWebhookEndpointRequest | 

    try:
        # Create a Webhook Endpoint
        api_response = api_instance.create_webhook_endpoint(create_webhook_endpoint_request)
        print("The response of WebhooksApi->create_webhook_endpoint:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WebhooksApi->create_webhook_endpoint: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **create_webhook_endpoint_request** | [**CreateWebhookEndpointRequest**](CreateWebhookEndpointRequest.md)|  | 

### Return type

[**CreateWebhookEndpoint200Response**](CreateWebhookEndpoint200Response.md)

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

# **delete_webhook_endpoint**
> RemoveAccount200Response delete_webhook_endpoint(id)

Delete a Webhook Endpoint

Deletes a webhook endpoint by ID.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.remove_account200_response import RemoveAccount200Response
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
    api_instance = unipile.WebhooksApi(api_client)
    id = 'id_example' # str | The ID of the Webhook Endpoint to delete.

    try:
        # Delete a Webhook Endpoint
        api_response = api_instance.delete_webhook_endpoint(id)
        print("The response of WebhooksApi->delete_webhook_endpoint:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WebhooksApi->delete_webhook_endpoint: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The ID of the Webhook Endpoint to delete. | 

### Return type

[**RemoveAccount200Response**](RemoveAccount200Response.md)

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

# **get_webhook_endpoint**
> CreateWebhookEndpoint200Response get_webhook_endpoint(id)

Get a Webhook Endpoint

Retrieves a webhook endpoint by ID.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_webhook_endpoint200_response import CreateWebhookEndpoint200Response
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
    api_instance = unipile.WebhooksApi(api_client)
    id = 'id_example' # str | The ID of the Webhook Endpoint to retrieve.

    try:
        # Get a Webhook Endpoint
        api_response = api_instance.get_webhook_endpoint(id)
        print("The response of WebhooksApi->get_webhook_endpoint:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WebhooksApi->get_webhook_endpoint: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The ID of the Webhook Endpoint to retrieve. | 

### Return type

[**CreateWebhookEndpoint200Response**](CreateWebhookEndpoint200Response.md)

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

# **list_webhook_conversations**
> ListWebhookConversations200Response list_webhook_conversations(endpoint_id, event_id=event_id, offset=offset, limit=limit)

List all Webhook Conversations

Returns a list of all Webhook Conversations associated with the current Application. The conversations are returned sorted by their creation date, with the most recent appearing first.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.list_webhook_conversations200_response import ListWebhookConversations200Response
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
    api_instance = unipile.WebhooksApi(api_client)
    endpoint_id = 'endpoint_id_example' # str | Filter to return only conversations for the given endpoint.
    event_id = 'event_id_example' # str | Filter to return only conversations for the given event. (optional)
    offset = 'offset_example' # str | An offset used for pagination. (optional)
    limit = 'limit_example' # str | A limit used for pagination. (optional)

    try:
        # List all Webhook Conversations
        api_response = api_instance.list_webhook_conversations(endpoint_id, event_id=event_id, offset=offset, limit=limit)
        print("The response of WebhooksApi->list_webhook_conversations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WebhooksApi->list_webhook_conversations: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **endpoint_id** | **str**| Filter to return only conversations for the given endpoint. | 
 **event_id** | **str**| Filter to return only conversations for the given event. | [optional] 
 **offset** | **str**| An offset used for pagination. | [optional] 
 **limit** | **str**| A limit used for pagination. | [optional] 

### Return type

[**ListWebhookConversations200Response**](ListWebhookConversations200Response.md)

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

# **list_webhook_endpoints**
> ListWebhookEndpoints200Response list_webhook_endpoints(offset=offset, limit=limit)

List all Webhook Endpoints

Returns a list of all Webhook Endpoints associated with the current Application.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.list_webhook_endpoints200_response import ListWebhookEndpoints200Response
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
    api_instance = unipile.WebhooksApi(api_client)
    offset = 'offset_example' # str | An offset used for pagination. (optional)
    limit = '20' # str | The limit of items to be returned. (optional) (default to '20')

    try:
        # List all Webhook Endpoints
        api_response = api_instance.list_webhook_endpoints(offset=offset, limit=limit)
        print("The response of WebhooksApi->list_webhook_endpoints:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WebhooksApi->list_webhook_endpoints: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **offset** | **str**| An offset used for pagination. | [optional] 
 **limit** | **str**| The limit of items to be returned. | [optional] [default to &#39;20&#39;]

### Return type

[**ListWebhookEndpoints200Response**](ListWebhookEndpoints200Response.md)

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

# **update_webhook_endpoint**
> CreateWebhookEndpoint200Response update_webhook_endpoint(id, update_webhook_endpoint_request=update_webhook_endpoint_request)

Update a Webhook Endpoint

Updates a webhook endpoint by ID.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_webhook_endpoint200_response import CreateWebhookEndpoint200Response
from unipile.models.update_webhook_endpoint_request import UpdateWebhookEndpointRequest
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
    api_instance = unipile.WebhooksApi(api_client)
    id = 'id_example' # str | The ID of the Webhook Endpoint to update.
    update_webhook_endpoint_request = unipile.UpdateWebhookEndpointRequest() # UpdateWebhookEndpointRequest |  (optional)

    try:
        # Update a Webhook Endpoint
        api_response = api_instance.update_webhook_endpoint(id, update_webhook_endpoint_request=update_webhook_endpoint_request)
        print("The response of WebhooksApi->update_webhook_endpoint:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling WebhooksApi->update_webhook_endpoint: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **str**| The ID of the Webhook Endpoint to update. | 
 **update_webhook_endpoint_request** | [**UpdateWebhookEndpointRequest**](UpdateWebhookEndpointRequest.md)|  | [optional] 

### Return type

[**CreateWebhookEndpoint200Response**](CreateWebhookEndpoint200Response.md)

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

