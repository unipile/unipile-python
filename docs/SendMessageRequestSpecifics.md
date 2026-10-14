# SendMessageRequestSpecifics

Object containing provider-specific message data.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**linkedin** | [**SendMessageRequestSpecificsLinkedin**](SendMessageRequestSpecificsLinkedin.md) |  | [optional] 

## Example

```python
from unipile.models.send_message_request_specifics import SendMessageRequestSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of SendMessageRequestSpecifics from a JSON string
send_message_request_specifics_instance = SendMessageRequestSpecifics.from_json(json)
# print the JSON string representation of the object
print(SendMessageRequestSpecifics.to_json())

# convert the object into a dict
send_message_request_specifics_dict = send_message_request_specifics_instance.to_dict()
# create an instance of SendMessageRequestSpecifics from a dict
send_message_request_specifics_from_dict = SendMessageRequestSpecifics.from_dict(send_message_request_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


