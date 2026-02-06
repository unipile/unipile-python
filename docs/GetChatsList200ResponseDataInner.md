# GetChatsList200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the chat for the provider. | 
**name** | **str** | The name / title of the chat. If the provider does not provide a name, name is built out of participants usernames. | 
**description** | **str** | The description / subject of the chat. | [optional] 
**image_url** | **str** | The URL of the chat image. | [optional] 
**created_at** | **str** | The creation date of the chat. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**updated_at** | **str** | The last update date of the chat. Use ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). Some providers update this field on new messages. | [optional] 
**last_message_timestamp** | **str** | The timestamp of the last message in the chat. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**muted_until** | [**GetChatsList200ResponseDataInnerMutedUntil**](GetChatsList200ResponseDataInnerMutedUntil.md) |  | 
**creator_id** | **str** | The ID of the user who created the chat. | [optional] 
**user_id** | **str** | The ID of the other participant in the chat if 1to1 chat. | [optional] 
**is_group** | **bool** | Is the chat a group chat. | 
**is_1to1** | **bool** | Is the chat a 1to1 chat. | 
**is_channel** | **bool** | Is the chat a channel chat. | 
**type** | **str** | The type of the chat.     - &#x60;group&#x60; is a group chat.     - &#x60;1to1&#x60; is a 1to1 chat.     - &#x60;channel&#x60; is a channel chat. | 
**is_pinned** | **bool** | Is the chat pinned at the top of the list, if supported by the provider. | 
**is_readonly** | **bool** | Is the chat read-only for the current user. Trying to send messages in read-only chats will fail. | 
**is_archived** | **bool** | Is the chat archived. Archived chats are usually hidden from the chat list. | 
**folders** | **List[Optional[str]]** | A list of folders the chat belongs to. | 
**participants_count** | **float** | The number of participants in the chat if the chat is a group. | [optional] 
**unread_count** | **float** | The number of unread messages in the chat. &#x60;0&#x60; if the chat is read, &#x60;-1&#x60; if the chat was manually marked as unread by the user and does not have any unread messages. | 
**restrictions** | **List[str]** | List of action restrictions of the chat.       - &#x60;send_message&#x60; is the permission to send messages. | [optional] 
**participants** | [**List[GetChatsList200ResponseDataInnerParticipantsInner]**](GetChatsList200ResponseDataInnerParticipantsInner.md) | List of participants in the chat if group chat. | [optional] 
**last_message** | [**GetChatsList200ResponseDataInnerLastMessage**](GetChatsList200ResponseDataInnerLastMessage.md) |  | [optional] 
**user** | [**GetChatsList200ResponseDataInnerUser**](GetChatsList200ResponseDataInnerUser.md) |  | [optional] 
**provider** | **str** | The provider&#39;s of the Account.     - &#x60;mock&#x60; is mock.     - &#x60;whatsapp&#x60; is WhatsApp.     - &#x60;linkedin&#x60; is LinkedIn.     - &#x60;instagram&#x60; is Instagram.     - &#x60;google&#x60; is Google.     - &#x60;outlook&#x60; is Outlook.     - &#x60;telegram&#x60; is Telegram.     - &#x60;imap&#x60; is IMAP. | 
**specifics** | **object** |  | [optional] 

## Example

```python
from unipile.models.get_chats_list200_response_data_inner import GetChatsList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatsList200ResponseDataInner from a JSON string
get_chats_list200_response_data_inner_instance = GetChatsList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetChatsList200ResponseDataInner.to_json())

# convert the object into a dict
get_chats_list200_response_data_inner_dict = get_chats_list200_response_data_inner_instance.to_dict()
# create an instance of GetChatsList200ResponseDataInner from a dict
get_chats_list200_response_data_inner_from_dict = GetChatsList200ResponseDataInner.from_dict(get_chats_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


