# EncryptedHistoryLastAttempt

Why the previous submission did not unlock the history. Absent the first time this checkpoint is served, so its presence is what tells the user their last answer failed.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**option** | **str** | PIN and RECOVERY_CODE unlock the end-to-end encrypted message history; SKIP leaves it off, and the account then only reports new messages as they arrive. | 
**error** | **str** | INVALID_CREDENTIAL: the PIN or recovery code was wrong, and one attempt was spent. REFUSED_TO_PROTECT_BACKUP: the PIN was not even submitted, because the provider had too few attempts left to risk one — no attempt was spent, and only the recovery code can unlock the history now. | 

## Example

```python
from unipile.models.encrypted_history_last_attempt import EncryptedHistoryLastAttempt

# TODO update the JSON string below
json = "{}"
# create an instance of EncryptedHistoryLastAttempt from a JSON string
encrypted_history_last_attempt_instance = EncryptedHistoryLastAttempt.from_json(json)
# print the JSON string representation of the object
print(EncryptedHistoryLastAttempt.to_json())

# convert the object into a dict
encrypted_history_last_attempt_dict = encrypted_history_last_attempt_instance.to_dict()
# create an instance of EncryptedHistoryLastAttempt from a dict
encrypted_history_last_attempt_from_dict = EncryptedHistoryLastAttempt.from_dict(encrypted_history_last_attempt_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


