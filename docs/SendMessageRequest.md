# SendMessageRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | The textual content of first message to be sent. It&#39;s recommended not to use HTML or Markdown. | 
**quote_id** | **str** | The ID of the Message to quote / reply to. | [optional] 
**attachments** | [**List[MessageFile]**](MessageFile.md) | The list of file attachments to the message to be sent in the chat. | [optional] 

## Example

```python
from unipile.models.send_message_request import SendMessageRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SendMessageRequest from a JSON string
send_message_request_instance = SendMessageRequest.from_json(json)
# print the JSON string representation of the object
print(SendMessageRequest.to_json())

# convert the object into a dict
send_message_request_dict = send_message_request_instance.to_dict()
# create an instance of SendMessageRequest from a dict
send_message_request_from_dict = SendMessageRequest.from_dict(send_message_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


