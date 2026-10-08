# TelegramRestrictionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**platform** | **str** | Platform the restriction applies to (e.g. &#x60;ios&#x60;, &#x60;android&#x60;, &#x60;all&#x60;). | 
**reason** | **str** | Machine readable reason of the restriction. | 
**text** | **str** | Human readable reason of the restriction. | 

## Example

```python
from unipile.models.telegram_restrictions_inner import TelegramRestrictionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of TelegramRestrictionsInner from a JSON string
telegram_restrictions_inner_instance = TelegramRestrictionsInner.from_json(json)
# print the JSON string representation of the object
print(TelegramRestrictionsInner.to_json())

# convert the object into a dict
telegram_restrictions_inner_dict = telegram_restrictions_inner_instance.to_dict()
# create an instance of TelegramRestrictionsInner from a dict
telegram_restrictions_inner_from_dict = TelegramRestrictionsInner.from_dict(telegram_restrictions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


