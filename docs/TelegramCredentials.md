# TelegramCredentials

The user credentials required by the provider to authenticate with.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**qrcode** | **bool** | This must be set to &#x60;true&#x60; | 
**twofa** | **str** | The 2FA code to authenticate with. | [optional] 

## Example

```python
from unipile.models.telegram_credentials import TelegramCredentials

# TODO update the JSON string below
json = "{}"
# create an instance of TelegramCredentials from a JSON string
telegram_credentials_instance = TelegramCredentials.from_json(json)
# print the JSON string representation of the object
print(TelegramCredentials.to_json())

# convert the object into a dict
telegram_credentials_dict = telegram_credentials_instance.to_dict()
# create an instance of TelegramCredentials from a dict
telegram_credentials_from_dict = TelegramCredentials.from_dict(telegram_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


