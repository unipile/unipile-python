# StartChatFromInboxRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | The textual content of the first message to be sent in the chat. It&#39;s recommended not to use HTML or Markdown. Use empty string to start a chat without a message (if supported by the provider). | 
**name** | **str** | A custom name for the chat. Some providers allow custom names only on groups. Default is made of participant names. | [optional] 
**users_ids** | [**StartChatFromInboxRequestUsersIds**](StartChatFromInboxRequestUsersIds.md) |  | 
**attachments** | [**List[MessageFile]**](MessageFile.md) | The list of file attachments to the message to be sent in the chat. | [optional] 
**specifics** | [**StartChatRequestSpecifics**](StartChatRequestSpecifics.md) |  | [optional] 

## Example

```python
from unipile.models.start_chat_from_inbox_request import StartChatFromInboxRequest

# TODO update the JSON string below
json = "{}"
# create an instance of StartChatFromInboxRequest from a JSON string
start_chat_from_inbox_request_instance = StartChatFromInboxRequest.from_json(json)
# print the JSON string representation of the object
print(StartChatFromInboxRequest.to_json())

# convert the object into a dict
start_chat_from_inbox_request_dict = start_chat_from_inbox_request_instance.to_dict()
# create an instance of StartChatFromInboxRequest from a dict
start_chat_from_inbox_request_from_dict = StartChatFromInboxRequest.from_dict(start_chat_from_inbox_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


