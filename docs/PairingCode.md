# PairingCode

A pairing code must be entered in the provider app to complete authentication.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**code** | **str** | The pairing code to enter on the phone to link the device. | 

## Example

```python
from unipile.models.pairing_code import PairingCode

# TODO update the JSON string below
json = "{}"
# create an instance of PairingCode from a JSON string
pairing_code_instance = PairingCode.from_json(json)
# print the JSON string representation of the object
print(PairingCode.to_json())

# convert the object into a dict
pairing_code_dict = pairing_code_instance.to_dict()
# create an instance of PairingCode from a dict
pairing_code_from_dict = PairingCode.from_dict(pairing_code_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


