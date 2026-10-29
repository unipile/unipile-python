# EncryptedHistoryOptionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | PIN and RECOVERY_CODE unlock the end-to-end encrypted message history; SKIP leaves it off, and the account then only reports new messages as they arrive. | 
**label** | **str** | Human-readable name of the option. | 
**description** | **str** | Extra detail about what the option entails. | [optional] 
**attempts_remaining** | **int** | How many more times this credential may be submitted. Each credential has a budget of its own, starting at 3, so running one out leaves the others open. A PIN is further capped at half of what the provider still allows, so the user can be wrong here without ever being the reason the backup locks. &#x60;0&#x60; means the option cannot be used any more; absent on options that take no credential. | [optional] 

## Example

```python
from unipile.models.encrypted_history_options_inner import EncryptedHistoryOptionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of EncryptedHistoryOptionsInner from a JSON string
encrypted_history_options_inner_instance = EncryptedHistoryOptionsInner.from_json(json)
# print the JSON string representation of the object
print(EncryptedHistoryOptionsInner.to_json())

# convert the object into a dict
encrypted_history_options_inner_dict = encrypted_history_options_inner_instance.to_dict()
# create an instance of EncryptedHistoryOptionsInner from a dict
encrypted_history_options_inner_from_dict = EncryptedHistoryOptionsInner.from_dict(encrypted_history_options_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


