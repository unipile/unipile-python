# PinMessageRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pin_status** | **bool** | Set to &#x60;true&#x60; to pin the message in the chat, or &#x60;false&#x60; to unpin it. | 
**specifics** | [**PinMessageRequestSpecifics**](PinMessageRequestSpecifics.md) |  | [optional] 

## Example

```python
from unipile.models.pin_message_request import PinMessageRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PinMessageRequest from a JSON string
pin_message_request_instance = PinMessageRequest.from_json(json)
# print the JSON string representation of the object
print(PinMessageRequest.to_json())

# convert the object into a dict
pin_message_request_dict = pin_message_request_instance.to_dict()
# create an instance of PinMessageRequest from a dict
pin_message_request_from_dict = PinMessageRequest.from_dict(pin_message_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


