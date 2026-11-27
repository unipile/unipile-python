# GetChatInviteLink200Response

The link that invites people to join a group chat or a community.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;InviteLink&#x60;. | 
**url** | **str** | The link that invites people to join. | 
**code** | **str** | The invite code of the link. *Join a Chat* or *Join a Community* accepts it, depending on what it invites to. | 

## Example

```python
from unipile.models.get_chat_invite_link200_response import GetChatInviteLink200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatInviteLink200Response from a JSON string
get_chat_invite_link200_response_instance = GetChatInviteLink200Response.from_json(json)
# print the JSON string representation of the object
print(GetChatInviteLink200Response.to_json())

# convert the object into a dict
get_chat_invite_link200_response_dict = get_chat_invite_link200_response_instance.to_dict()
# create an instance of GetChatInviteLink200Response from a dict
get_chat_invite_link200_response_from_dict = GetChatInviteLink200Response.from_dict(get_chat_invite_link200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


