# Passkey

An additional passkey verification required to finish linking this account. Poll the checkpoint with an empty code; confirm only with CONFIRM followed by a colon and the exact displayed comparison code. CANCEL abandons this attempt.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | An owner-authorized browser verification is required. | 
**stage** | **str** | Whether to verify in the browser or compare and approve the mobile confirmation. | 
**request_id** | **str** | Opaque identifier of this single-use verification step. | 
**expires_at** | **str** | Expiry of this verification attempt, in ISO 8601 format. | 
**comparison_code** | **str** | Compare this code with the code on your phone before approving. | [optional] 
**handoff** | [**PasskeyHandoff**](PasskeyHandoff.md) |  | [optional] 
**unavailable** | **str** | The verification service is not ready; retry after its update. Ordinary authentication methods remain available. | [optional] 

## Example

```python
from unipile.models.passkey import Passkey

# TODO update the JSON string below
json = "{}"
# create an instance of Passkey from a JSON string
passkey_instance = Passkey.from_json(json)
# print the JSON string representation of the object
print(Passkey.to_json())

# convert the object into a dict
passkey_dict = passkey_instance.to_dict()
# create an instance of Passkey from a dict
passkey_from_dict = Passkey.from_dict(passkey_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


