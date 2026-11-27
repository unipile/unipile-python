# GetCommunityChatsList200ResponseDataInner

Summary of a group chat linked to a community. Use its `id` as `chat_id` in the Messaging API.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;Chat&#x60;. | 
**id** | **str** | The unique identifier of the chat for the provider. | 
**name** | **str** | The name / title of the chat. If the provider does not provide a name, name is built out of participants usernames. | 
**provider** | **str** | The provider&#39;s of the Account.     - &#x60;mock&#x60; is mock.     - &#x60;whatsapp&#x60; is WhatsApp.     - &#x60;linkedin&#x60; is LinkedIn.     - &#x60;instagram&#x60; is Instagram.     - &#x60;facebook&#x60; is Facebook.     - &#x60;google&#x60; is Google.     - &#x60;outlook&#x60; is Outlook.     - &#x60;telegram&#x60; is Telegram.     - &#x60;imap&#x60; is IMAP. | 
**participants_count** | **float** | The number of participants in the chat if the chat is a group. | [optional] 
**created_at** | **str** | The creation date of the chat. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**creator_id** | **str** | The ID of the user who created the chat. | [optional] 
**type** | **str** | The type of the linked chat. | 

## Example

```python
from unipile.models.get_community_chats_list200_response_data_inner import GetCommunityChatsList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetCommunityChatsList200ResponseDataInner from a JSON string
get_community_chats_list200_response_data_inner_instance = GetCommunityChatsList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetCommunityChatsList200ResponseDataInner.to_json())

# convert the object into a dict
get_community_chats_list200_response_data_inner_dict = get_community_chats_list200_response_data_inner_instance.to_dict()
# create an instance of GetCommunityChatsList200ResponseDataInner from a dict
get_community_chats_list200_response_data_inner_from_dict = GetCommunityChatsList200ResponseDataInner.from_dict(get_community_chats_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


