# GetChatsList200ResponseDataInnerLastMessageAnyOf1Quoted

The quoted message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the message for the provider. | 
**text** | **str** | The text content of the message. | [optional] 
**attachments** | [**List[GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner]**](GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner.md) | List of message attachments. | 
**sender** | [**GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender**](GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender.md) |  | [optional] 

## Example

```python
from unipile.models.get_chats_list200_response_data_inner_last_message_any_of1_quoted import GetChatsList200ResponseDataInnerLastMessageAnyOf1Quoted

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf1Quoted from a JSON string
get_chats_list200_response_data_inner_last_message_any_of1_quoted_instance = GetChatsList200ResponseDataInnerLastMessageAnyOf1Quoted.from_json(json)
# print the JSON string representation of the object
print(GetChatsList200ResponseDataInnerLastMessageAnyOf1Quoted.to_json())

# convert the object into a dict
get_chats_list200_response_data_inner_last_message_any_of1_quoted_dict = get_chats_list200_response_data_inner_last_message_any_of1_quoted_instance.to_dict()
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf1Quoted from a dict
get_chats_list200_response_data_inner_last_message_any_of1_quoted_from_dict = GetChatsList200ResponseDataInnerLastMessageAnyOf1Quoted.from_dict(get_chats_list200_response_data_inner_last_message_any_of1_quoted_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


