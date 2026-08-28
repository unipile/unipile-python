# Telegram

Telegram specific dataset for user profiles.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**is_mutual_contact** | **bool** | Whether the user and the account owner are in each other address book. | 
**is_close_friend** | **bool** | Whether the user is a close friend of the account owner. | 
**is_bot** | **bool** | Whether the user is a bot. | 
**is_support** | **bool** | Whether the user is an official Telegram support account. | 
**is_scam** | **bool** | Whether the user has been flagged as a scam by Telegram. | 
**is_fake** | **bool** | Whether the user has been flagged as impersonating another user by Telegram. | 
**is_restricted** | **bool** | Whether the user is restricted on some platforms. | 
**restrictions** | [**List[TelegramRestrictionsInner]**](TelegramRestrictionsInner.md) | Restrictions applied to the user, if any. | [optional] 
**status** | [**TelegramStatus**](TelegramStatus.md) |  | [optional] 
**common_chats_count** | **float** | Number of chats shared between the user and the account owner. | [optional] 

## Example

```python
from unipile.models.telegram import Telegram

# TODO update the JSON string below
json = "{}"
# create an instance of Telegram from a JSON string
telegram_instance = Telegram.from_json(json)
# print the JSON string representation of the object
print(Telegram.to_json())

# convert the object into a dict
telegram_dict = telegram_instance.to_dict()
# create an instance of Telegram from a dict
telegram_from_dict = Telegram.from_dict(telegram_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


