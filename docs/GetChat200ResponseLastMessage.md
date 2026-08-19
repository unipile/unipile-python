# GetChat200ResponseLastMessage

The last message in the chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the message for the provider. | 
**text** | **str** | The text content of the message. | 
**sender_display_name** | **str** | The display name of the sender of the message. | [optional] 
**is_sender** | **bool** | Is the current user the sender of the message. | 
**sender_id** | **str** | The ID of the user who sent the message. | 
**chat_id** | **str** | The ID of the chat where the message was sent. | 
**timestamp** | **str** | The timestamp of the message. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**is_hidden** | **bool** | Is the message hidden. Hidden messages are usually not displayed in the chat but can be as last message is chats list. | 
**is_seen** | **bool** | Is the message seen by other participants. | 
**is_delivered** | **bool** | Is the message delivered to the other participants. | 
**is_deleted** | **bool** | Is the message deleted. Some providers show the message as deleted in the chat. | 
**is_edited** | **bool** | Is the message edited. Some providers adds an \&quot;edited\&quot; mark on the message in the chat. | 
**is_pinned** | **bool** | Is the message pinned. Pinned messages are usually displayed at the top of the chat. | 
**is_event** | **bool** | Is the message an event. Events are special messages that are not displayed in the chat but can be used to trigger actions. | 
**is_mentionned** | **bool** | Is the message mentionning the current user. Usually to notify. | 
**event_type** | **float** | The type of message event.     0 : Unknown (Not implemented)     1 : Chat name update     2 : Chat description update     3 : New participant added to the chat group     4 : Participant kicked or left the chat group     5 : A message is pinned     6 : Permissions have been updated     7 : Participant was promoted or demoted     8 : Reaction     9 : Call Missed     10 : Call Started     11 : Call Ended     12 : Call Rejected     13 : Scheduled Call Created     14 : Scheduled Call Cancelled     15 : Scheduled Call Started     16 : Announcement      | [optional] 
**event_metadata** | [**GetChatsList200ResponseDataInnerLastMessageAnyOf1EventMetadata**](GetChatsList200ResponseDataInnerLastMessageAnyOf1EventMetadata.md) |  | [optional] 
**reactions_counter** | [**List[GetChatsList200ResponseDataInnerLastMessageAnyOf1ReactionsCounterInner]**](GetChatsList200ResponseDataInnerLastMessageAnyOf1ReactionsCounterInner.md) | A list of reactions to the element. | 
**sender** | [**GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender**](GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender.md) |  | [optional] 
**provider** | **str** | The provider&#39;s of the Account.     - &#x60;mock&#x60; is mock.     - &#x60;whatsapp&#x60; is WhatsApp.     - &#x60;linkedin&#x60; is LinkedIn.     - &#x60;instagram&#x60; is Instagram.     - &#x60;google&#x60; is Google.     - &#x60;outlook&#x60; is Outlook.     - &#x60;telegram&#x60; is Telegram.     - &#x60;imap&#x60; is IMAP. | 
**attachments** | [**List[GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner]**](GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner.md) | List of message attachments. | 
**hyperlinks** | [**List[GetChatsList200ResponseDataInnerLastMessageAnyOf1HyperlinksInner]**](GetChatsList200ResponseDataInnerLastMessageAnyOf1HyperlinksInner.md) | List of message hyperlinks. | 
**quoted** | [**GetChatsList200ResponseDataInnerLastMessageAnyOf1Quoted**](GetChatsList200ResponseDataInnerLastMessageAnyOf1Quoted.md) |  | [optional] 
**forwarded** | [**GetChatsList200ResponseDataInnerLastMessageAnyOf1Forwarded**](GetChatsList200ResponseDataInnerLastMessageAnyOf1Forwarded.md) |  | [optional] 
**specifics** | **object** |  | [optional] 

## Example

```python
from unipile.models.get_chat200_response_last_message import GetChat200ResponseLastMessage

# TODO update the JSON string below
json = "{}"
# create an instance of GetChat200ResponseLastMessage from a JSON string
get_chat200_response_last_message_instance = GetChat200ResponseLastMessage.from_json(json)
# print the JSON string representation of the object
print(GetChat200ResponseLastMessage.to_json())

# convert the object into a dict
get_chat200_response_last_message_dict = get_chat200_response_last_message_instance.to_dict()
# create an instance of GetChat200ResponseLastMessage from a dict
get_chat200_response_last_message_from_dict = GetChat200ResponseLastMessage.from_dict(get_chat200_response_last_message_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


