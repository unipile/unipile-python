# AutomaticProxyConfiguration

Configuration to infer the automatically allocated proxy's location. If not provided, Unipile will dynamically infer the proxy's location based on the public IP of the service, when a problem is detected with another proxy, and it would not be possible to automatically infer the proxy's location from the public IP.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**country** | **str** | An ISO 3166-1 A-2 country code to be set as automatic proxy&#39;s location. | [optional] 
**ip** | **str** | An IPv4 address to infer proxy&#39;s location. | [optional] 

## Example

```python
from unipile.models.automatic_proxy_configuration import AutomaticProxyConfiguration

# TODO update the JSON string below
json = "{}"
# create an instance of AutomaticProxyConfiguration from a JSON string
automatic_proxy_configuration_instance = AutomaticProxyConfiguration.from_json(json)
# print the JSON string representation of the object
print(AutomaticProxyConfiguration.to_json())

# convert the object into a dict
automatic_proxy_configuration_dict = automatic_proxy_configuration_instance.to_dict()
# create an instance of AutomaticProxyConfiguration from a dict
automatic_proxy_configuration_from_dict = AutomaticProxyConfiguration.from_dict(automatic_proxy_configuration_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


