# PinMessageRequestSpecificsWhatsapp

Specific options for pinning a WhatsApp message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pin_duration** | **str** | How long the message should stay pinned, Whatsapp unpinning it by itself once elapsed.         - &#x60;24_hours&#x60; for a day.         - &#x60;7_days&#x60; for a week.         - &#x60;30_days&#x60; for a month. | [optional] [default to '30_days']

## Example

```python
from unipile.models.pin_message_request_specifics_whatsapp import PinMessageRequestSpecificsWhatsapp

# TODO update the JSON string below
json = "{}"
# create an instance of PinMessageRequestSpecificsWhatsapp from a JSON string
pin_message_request_specifics_whatsapp_instance = PinMessageRequestSpecificsWhatsapp.from_json(json)
# print the JSON string representation of the object
print(PinMessageRequestSpecificsWhatsapp.to_json())

# convert the object into a dict
pin_message_request_specifics_whatsapp_dict = pin_message_request_specifics_whatsapp_instance.to_dict()
# create an instance of PinMessageRequestSpecificsWhatsapp from a dict
pin_message_request_specifics_whatsapp_from_dict = PinMessageRequestSpecificsWhatsapp.from_dict(pin_message_request_specifics_whatsapp_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


