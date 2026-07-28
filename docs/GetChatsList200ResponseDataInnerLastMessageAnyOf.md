# GetChatsList200ResponseDataInnerLastMessageAnyOf


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the message. | [optional] 
**text** | **str** | The text content of the message. | 
**sender_display_name** | **str** | The display name of the sender of the message. | [optional] 
**is_sender** | **bool** | Is the message sent by the current user. | [optional] 

## Example

```python
from unipile.models.get_chats_list200_response_data_inner_last_message_any_of import GetChatsList200ResponseDataInnerLastMessageAnyOf

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf from a JSON string
get_chats_list200_response_data_inner_last_message_any_of_instance = GetChatsList200ResponseDataInnerLastMessageAnyOf.from_json(json)
# print the JSON string representation of the object
print(GetChatsList200ResponseDataInnerLastMessageAnyOf.to_json())

# convert the object into a dict
get_chats_list200_response_data_inner_last_message_any_of_dict = get_chats_list200_response_data_inner_last_message_any_of_instance.to_dict()
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf from a dict
get_chats_list200_response_data_inner_last_message_any_of_from_dict = GetChatsList200ResponseDataInnerLastMessageAnyOf.from_dict(get_chats_list200_response_data_inner_last_message_any_of_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


