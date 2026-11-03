# GetChatsList200ResponseDataInnerLastMessageAnyOf1MentionsInner

The parameters of a user mention contained in the body.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | ID of the mentioned user, which can be used to mention them when sending a message. Absent when the provider reports the mention without an identifier, or when the mention addresses the whole chat rather than a user. | [optional] 
**url** | **str** | Public profile URL of the mentioned user. Absent when the provider exposes no public profile for them. | [optional] 
**start** | **float** | The index in the body where the mention starts. | 
**length** | **float** | The number of characters in the body that make up the mention, starting at the &#x60;start&#x60; index. | 

## Example

```python
from unipile.models.get_chats_list200_response_data_inner_last_message_any_of1_mentions_inner import GetChatsList200ResponseDataInnerLastMessageAnyOf1MentionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf1MentionsInner from a JSON string
get_chats_list200_response_data_inner_last_message_any_of1_mentions_inner_instance = GetChatsList200ResponseDataInnerLastMessageAnyOf1MentionsInner.from_json(json)
# print the JSON string representation of the object
print(GetChatsList200ResponseDataInnerLastMessageAnyOf1MentionsInner.to_json())

# convert the object into a dict
get_chats_list200_response_data_inner_last_message_any_of1_mentions_inner_dict = get_chats_list200_response_data_inner_last_message_any_of1_mentions_inner_instance.to_dict()
# create an instance of GetChatsList200ResponseDataInnerLastMessageAnyOf1MentionsInner from a dict
get_chats_list200_response_data_inner_last_message_any_of1_mentions_inner_from_dict = GetChatsList200ResponseDataInnerLastMessageAnyOf1MentionsInner.from_dict(get_chats_list200_response_data_inner_last_message_any_of1_mentions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


