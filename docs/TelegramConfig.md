# TelegramConfig

Telegram specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 

## Example

```python
from unipile.models.telegram_config import TelegramConfig

# TODO update the JSON string below
json = "{}"
# create an instance of TelegramConfig from a JSON string
telegram_config_instance = TelegramConfig.from_json(json)
# print the JSON string representation of the object
print(TelegramConfig.to_json())

# convert the object into a dict
telegram_config_dict = telegram_config_instance.to_dict()
# create an instance of TelegramConfig from a dict
telegram_config_from_dict = TelegramConfig.from_dict(telegram_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


