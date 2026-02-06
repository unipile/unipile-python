# GetChatsList200ResponseDataInnerLastMessage

The last message in the chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | The text content of the last message in the chat. | 
**sender_display_name** | **str** | The display name of the sender of the last message in the chat in group chats. | [optional] 
**is_sender** | **bool** | Is the last message sent by the current user. | 

## Example

```python
from unipile.models.get_chats_list200_response_data_inner_last_message import GetChatsList200ResponseDataInnerLastMessage

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatsList200ResponseDataInnerLastMessage from a JSON string
get_chats_list200_response_data_inner_last_message_instance = GetChatsList200ResponseDataInnerLastMessage.from_json(json)
# print the JSON string representation of the object
print(GetChatsList200ResponseDataInnerLastMessage.to_json())

# convert the object into a dict
get_chats_list200_response_data_inner_last_message_dict = get_chats_list200_response_data_inner_last_message_instance.to_dict()
# create an instance of GetChatsList200ResponseDataInnerLastMessage from a dict
get_chats_list200_response_data_inner_last_message_from_dict = GetChatsList200ResponseDataInnerLastMessage.from_dict(get_chats_list200_response_data_inner_last_message_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


