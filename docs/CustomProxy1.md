# CustomProxy1

A custom proxy to connect through to the account provider. For supported providers, if not given, Unipile will automatically manage the proxy. In this case, the given custom proxy will override the automatic proxy. Read more about it in the Proxy documentation.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**host** | **str** | The host of the proxy. | 
**port** | **float** | The port of the proxy. | 
**username** | **str** | The username to connect to the proxy. | [optional] 
**password** | **str** | The password to connect to the proxy. | [optional] 
**protocol** | **str** | The protocol of the proxy.         - &#x60;https&#x60; is HTTPS.         - &#x60;http&#x60; is HTTP.           - &#x60;socks5&#x60; is SOCKS5.           - &#x60;socks4&#x60; is SOCKS4. | 

## Example

```python
from unipile.models.custom_proxy1 import CustomProxy1

# TODO update the JSON string below
json = "{}"
# create an instance of CustomProxy1 from a JSON string
custom_proxy1_instance = CustomProxy1.from_json(json)
# print the JSON string representation of the object
print(CustomProxy1.to_json())

# convert the object into a dict
custom_proxy1_dict = custom_proxy1_instance.to_dict()
# create an instance of CustomProxy1 from a dict
custom_proxy1_from_dict = CustomProxy1.from_dict(custom_proxy1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


