# TelegramStatus

Last seen status of the user, as exposed by Telegram.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Last seen status of the user.       - &#x60;online&#x60; the user is currently online, until &#x60;expires_at&#x60;.       - &#x60;offline&#x60; the user is offline, and was last online at &#x60;was_online_at&#x60;.       - &#x60;recently&#x60;, &#x60;last_week&#x60; and &#x60;last_month&#x60; are the approximations returned when the user hides its exact last seen date. | 
**expires_at** | **str** | Date and time until when the user is considered online (&#x60;online&#x60; status only). | [optional] 
**was_online_at** | **str** | Date and time when the user was last online (&#x60;offline&#x60; status only). | [optional] 

## Example

```python
from unipile.models.telegram_status import TelegramStatus

# TODO update the JSON string below
json = "{}"
# create an instance of TelegramStatus from a JSON string
telegram_status_instance = TelegramStatus.from_json(json)
# print the JSON string representation of the object
print(TelegramStatus.to_json())

# convert the object into a dict
telegram_status_dict = telegram_status_instance.to_dict()
# create an instance of TelegramStatus from a dict
telegram_status_from_dict = TelegramStatus.from_dict(telegram_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


