# SendMessage200ResponseMessageId

The ID of the message sent. Some providers send attachments separately from the text content, which can result in multiple sent message IDs.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.send_message200_response_message_id import SendMessage200ResponseMessageId

# TODO update the JSON string below
json = "{}"
# create an instance of SendMessage200ResponseMessageId from a JSON string
send_message200_response_message_id_instance = SendMessage200ResponseMessageId.from_json(json)
# print the JSON string representation of the object
print(SendMessage200ResponseMessageId.to_json())

# convert the object into a dict
send_message200_response_message_id_dict = send_message200_response_message_id_instance.to_dict()
# create an instance of SendMessage200ResponseMessageId from a dict
send_message200_response_message_id_from_dict = SendMessage200ResponseMessageId.from_dict(send_message200_response_message_id_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


