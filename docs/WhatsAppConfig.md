# WhatsAppConfig

WhatsApp specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 

## Example

```python
from unipile.models.whats_app_config import WhatsAppConfig

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsAppConfig from a JSON string
whats_app_config_instance = WhatsAppConfig.from_json(json)
# print the JSON string representation of the object
print(WhatsAppConfig.to_json())

# convert the object into a dict
whats_app_config_dict = whats_app_config_instance.to_dict()
# create an instance of WhatsAppConfig from a dict
whats_app_config_from_dict = WhatsAppConfig.from_dict(whats_app_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


