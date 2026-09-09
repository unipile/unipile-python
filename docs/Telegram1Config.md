# Telegram1Config

Telegram specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 

## Example

```python
from unipile.models.telegram1_config import Telegram1Config

# TODO update the JSON string below
json = "{}"
# create an instance of Telegram1Config from a JSON string
telegram1_config_instance = Telegram1Config.from_json(json)
# print the JSON string representation of the object
print(Telegram1Config.to_json())

# convert the object into a dict
telegram1_config_dict = telegram1_config_instance.to_dict()
# create an instance of Telegram1Config from a dict
telegram1_config_from_dict = Telegram1Config.from_dict(telegram1_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


