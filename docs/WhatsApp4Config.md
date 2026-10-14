# WhatsApp4Config

WhatsApp specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 

## Example

```python
from unipile.models.whats_app4_config import WhatsApp4Config

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsApp4Config from a JSON string
whats_app4_config_instance = WhatsApp4Config.from_json(json)
# print the JSON string representation of the object
print(WhatsApp4Config.to_json())

# convert the object into a dict
whats_app4_config_dict = whats_app4_config_instance.to_dict()
# create an instance of WhatsApp4Config from a dict
whats_app4_config_from_dict = WhatsApp4Config.from_dict(whats_app4_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


