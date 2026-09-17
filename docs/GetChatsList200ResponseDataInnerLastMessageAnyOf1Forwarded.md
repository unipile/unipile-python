# GetChatsList200ResponseDataInnerLastMessageAnyOf1Forwarded

Contains the original message if this message was forwarded from another chat, depending on provider support.     Some providers preserve the original sender and content, treating it as if it were sent by the account owner.     Others wrap the forwarded message within a new message (similar to a quote or attachment), in which case the original message appears here.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | The text content of the message. | [optional] 
**attachments** | [**List[GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner]**](GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner.md) | List of message attachments. | 
**sender** | [**GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender**](GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender.md) |  | [optional] 
**object** | **str** |  | 

## Example

```python
from unipile.models.get_chats_list200_response_data_inner_last_message_any_of1_forwarded import GetChatsList200ResponseDataInnerLastMessageAnyOf1Forwarded

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf1Forwarded from a JSON string
get_chats_list200_response_data_inner_last_message_any_of1_forwarded_instance = GetChatsList200ResponseDataInnerLastMessageAnyOf1Forwarded.from_json(json)
# print the JSON string representation of the object
print(GetChatsList200ResponseDataInnerLastMessageAnyOf1Forwarded.to_json())

# convert the object into a dict
get_chats_list200_response_data_inner_last_message_any_of1_forwarded_dict = get_chats_list200_response_data_inner_last_message_any_of1_forwarded_instance.to_dict()
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf1Forwarded from a dict
get_chats_list200_response_data_inner_last_message_any_of1_forwarded_from_dict = GetChatsList200ResponseDataInnerLastMessageAnyOf1Forwarded.from_dict(get_chats_list200_response_data_inner_last_message_any_of1_forwarded_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


