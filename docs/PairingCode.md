# PairingCode

Authenticate by entering a pairing code on the WhatsApp mobile app.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **str** | Phone number to link, in international format with digits only (no &#x60;+&#x60;, spaces or separators), e.g. &#x60;33612345678&#x60;. A pairing code will be returned to enter on this phone. | 

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


