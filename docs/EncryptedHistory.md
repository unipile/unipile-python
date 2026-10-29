# EncryptedHistory

The user must choose whether to unlock the end-to-end encrypted message history, and with which credential.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**options** | [**List[EncryptedHistoryOptionsInner]**](EncryptedHistoryOptionsInner.md) | The ways the user can answer. Send the chosen &#x60;id&#x60; as the &#x60;code&#x60; of Solve Checkpoint. | 
**attempts_remaining** | **int** | The most submissions any credential still has — what the user has left overall. &#x60;0&#x60; means every credential is spent and only skipping remains. The detail per credential is in &#x60;options[].attempts_remaining&#x60;; a credential the provider refuses to even try does not consume one. | 
**provider_attempts_remaining** | **int** | For a PIN, how many attempts the provider itself still allows before it locks the backup. This budget is the provider&#39;s own and is never spent on the user&#39;s behalf: when it is unknown or too low, the PIN is refused rather than tried. | [optional] 
**last_attempt** | [**EncryptedHistoryLastAttempt**](EncryptedHistoryLastAttempt.md) |  | [optional] 

## Example

```python
from unipile.models.encrypted_history import EncryptedHistory

# TODO update the JSON string below
json = "{}"
# create an instance of EncryptedHistory from a JSON string
encrypted_history_instance = EncryptedHistory.from_json(json)
# print the JSON string representation of the object
print(EncryptedHistory.to_json())

# convert the object into a dict
encrypted_history_dict = encrypted_history_instance.to_dict()
# create an instance of EncryptedHistory from a dict
encrypted_history_from_dict = EncryptedHistory.from_dict(encrypted_history_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


