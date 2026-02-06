# unipile.InstagramApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**search_locations**](InstagramApi.md#search_locations) | **GET** /v2/{account_id}/instagram/search/locations | Search locations


# **search_locations**
> List[SearchLocations200ResponseInner] search_locations(account_id, latitude=latitude, longitude=longitude, search_query=search_query)

Search locations

Return a list of Instagram locations. Use `latitude` and `longitude` to orient search query results by influencing their relevance ranking. When a search query is performed, locations that are considered most relevant in relation to the provided geographic coordinates are prioritized in the results. This can be used to tag a Post with a location.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.search_locations200_response_inner import SearchLocations200ResponseInner
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
    api_instance = unipile.InstagramApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    latitude = 48.8566 # float | The latitude coordinate to orient search query results by influencing their relevance ranking. (optional)
    longitude = 2.3522 # float | The longitude coordinate to orient search query results by influencing their relevance ranking. (optional)
    search_query = 'Paris' # str | The search query to filter locations by name. (optional)

    try:
        # Search locations
        api_response = api_instance.search_locations(account_id, latitude=latitude, longitude=longitude, search_query=search_query)
        print("The response of InstagramApi->search_locations:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling InstagramApi->search_locations: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **latitude** | **float**| The latitude coordinate to orient search query results by influencing their relevance ranking. | [optional] 
 **longitude** | **float**| The longitude coordinate to orient search query results by influencing their relevance ranking. | [optional] 
 **search_query** | **str**| The search query to filter locations by name. | [optional] 

### Return type

[**List[SearchLocations200ResponseInner]**](SearchLocations200ResponseInner.md)

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

