# CustomProxy

A custom proxy used to connect to the account provider. When Automatic Proxy Protection applies to the provider, Unipile manages the proxy by default. A custom proxy overrides Automatic Proxy Protection. Read more in the Proxy documentation.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**host** | **str** | The hostname or IP address of the proxy, without a scheme, port, path or credentials. Enclose IPv6 addresses in brackets. | 
**port** | **int** | The port of the proxy, between 1 and 65535. | 
**username** | **str** | The username to connect to the proxy. Omitted, null or empty credentials select unauthenticated access when both credentials are absent. SOCKS5 requires both a non-empty username and password for authentication, each at most 255 bytes. | [optional] 
**password** | **str** | The password to connect to the proxy. Omitted, null or empty credentials select unauthenticated access when both credentials are absent. SOCKS5 requires both a non-empty username and password for authentication, each at most 255 bytes. HTTP Basic authentication permits an empty username or password. | [optional] 
**protocol** | **str** | The protocol of the proxy. Defaults to &#x60;https&#x60;.         - &#x60;https&#x60; is HTTPS.         - &#x60;http&#x60; is HTTP.           - &#x60;socks5&#x60; is SOCKS5.           - &#x60;socks4&#x60; is SOCKS4. | [optional] [default to 'https']

## Example

```python
from unipile.models.custom_proxy import CustomProxy

# TODO update the JSON string below
json = "{}"
# create an instance of CustomProxy from a JSON string
custom_proxy_instance = CustomProxy.from_json(json)
# print the JSON string representation of the object
print(CustomProxy.to_json())

# convert the object into a dict
custom_proxy_dict = custom_proxy_instance.to_dict()
# create an instance of CustomProxy from a dict
custom_proxy_from_dict = CustomProxy.from_dict(custom_proxy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


