# WhatsApp2Config

WhatsApp specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 

## Example

```python
from unipile.models.whats_app2_config import WhatsApp2Config

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsApp2Config from a JSON string
whats_app2_config_instance = WhatsApp2Config.from_json(json)
# print the JSON string representation of the object
print(WhatsApp2Config.to_json())

# convert the object into a dict
whats_app2_config_dict = whats_app2_config_instance.to_dict()
# create an instance of WhatsApp2Config from a dict
whats_app2_config_from_dict = WhatsApp2Config.from_dict(whats_app2_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


