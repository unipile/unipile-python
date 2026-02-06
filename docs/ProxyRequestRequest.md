# ProxyRequestRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**url** | **str** | The specific LinkedIn public API endpoint you need to call. Path variables can be declared with the &#x60;:VARIABLE_NAME&#x60; syntax. | 
**method** | **str** | The HTTP method to use when performing the request. | 
**body** | **Dict[str, object]** | A body object to send in the request. | [optional] 
**headers** | **Dict[str, Optional[str]]** | A headers object to include in the request. | [optional] 
**path_variables** | **Dict[str, Optional[str]]** | The Path variables that have been declared in the URL. Each variable must have a corresponding VARIABLE_NAME key to be injected in the URL. | [optional] 
**var_query_params** | **Dict[str, Optional[str]]** | Query parameters to include in the request URL. | [optional] 
**bypass_url_encoding** | **bool** | Whether to bypass URL encoding for query parameters or form-urlencoded body, so you can handle encoding yourself. | [optional] [default to False]

## Example

```python
from unipile.models.proxy_request_request import ProxyRequestRequest

# TODO update the JSON string below
json = "{}"
# create an instance of ProxyRequestRequest from a JSON string
proxy_request_request_instance = ProxyRequestRequest.from_json(json)
# print the JSON string representation of the object
print(ProxyRequestRequest.to_json())

# convert the object into a dict
proxy_request_request_dict = proxy_request_request_instance.to_dict()
# create an instance of ProxyRequestRequest from a dict
proxy_request_request_from_dict = ProxyRequestRequest.from_dict(proxy_request_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


