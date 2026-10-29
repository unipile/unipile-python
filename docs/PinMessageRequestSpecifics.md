# PinMessageRequestSpecifics

Object containing provider-specific pin data.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**whatsapp** | [**PinMessageRequestSpecificsWhatsapp**](PinMessageRequestSpecificsWhatsapp.md) |  | [optional] 

## Example

```python
from unipile.models.pin_message_request_specifics import PinMessageRequestSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of PinMessageRequestSpecifics from a JSON string
pin_message_request_specifics_instance = PinMessageRequestSpecifics.from_json(json)
# print the JSON string representation of the object
print(PinMessageRequestSpecifics.to_json())

# convert the object into a dict
pin_message_request_specifics_dict = pin_message_request_specifics_instance.to_dict()
# create an instance of PinMessageRequestSpecifics from a dict
pin_message_request_specifics_from_dict = PinMessageRequestSpecifics.from_dict(pin_message_request_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


