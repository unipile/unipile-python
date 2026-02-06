# StartChat200ResponseMessageId

The ID of the message sent. Some providers send attachments separately from the text content, which can result in multiple sent message IDs. If no message was sent, the value is `null`.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------

## Example

```python
from unipile.models.start_chat200_response_message_id import StartChat200ResponseMessageId

# TODO update the JSON string below
json = "{}"
# create an instance of StartChat200ResponseMessageId from a JSON string
start_chat200_response_message_id_instance = StartChat200ResponseMessageId.from_json(json)
# print the JSON string representation of the object
print(StartChat200ResponseMessageId.to_json())

# convert the object into a dict
start_chat200_response_message_id_dict = start_chat200_response_message_id_instance.to_dict()
# create an instance of StartChat200ResponseMessageId from a dict
start_chat200_response_message_id_from_dict = StartChat200ResponseMessageId.from_dict(start_chat200_response_message_id_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


