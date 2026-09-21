# PairingCode1

Authenticate by entering a pairing code on the WhatsApp mobile app.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **str** | Phone number to link, in international format with digits only (no &#x60;+&#x60;, spaces or separators), e.g. &#x60;33612345678&#x60;. A pairing code will be returned to enter on this phone. | 

## Example

```python
from unipile.models.pairing_code1 import PairingCode1

# TODO update the JSON string below
json = "{}"
# create an instance of PairingCode1 from a JSON string
pairing_code1_instance = PairingCode1.from_json(json)
# print the JSON string representation of the object
print(PairingCode1.to_json())

# convert the object into a dict
pairing_code1_dict = pairing_code1_instance.to_dict()
# create an instance of PairingCode1 from a dict
pairing_code1_from_dict = PairingCode1.from_dict(pairing_code1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


