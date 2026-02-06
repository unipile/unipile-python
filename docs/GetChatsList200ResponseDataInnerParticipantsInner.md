# GetChatsList200ResponseDataInnerParticipantsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**user** | [**GetChatsList200ResponseDataInnerParticipantsInnerUser**](GetChatsList200ResponseDataInnerParticipantsInnerUser.md) |  | 
**is_self** | **bool** | Is the current user the participant. | 
**is_admin** | **bool** | Is the participant an admin of the group. | 

## Example

```python
from unipile.models.get_chats_list200_response_data_inner_participants_inner import GetChatsList200ResponseDataInnerParticipantsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetChatsList200ResponseDataInnerParticipantsInner from a JSON string
get_chats_list200_response_data_inner_participants_inner_instance = GetChatsList200ResponseDataInnerParticipantsInner.from_json(json)
# print the JSON string representation of the object
print(GetChatsList200ResponseDataInnerParticipantsInner.to_json())

# convert the object into a dict
get_chats_list200_response_data_inner_participants_inner_dict = get_chats_list200_response_data_inner_participants_inner_instance.to_dict()
# create an instance of GetChatsList200ResponseDataInnerParticipantsInner from a dict
get_chats_list200_response_data_inner_participants_inner_from_dict = GetChatsList200ResponseDataInnerParticipantsInner.from_dict(get_chats_list200_response_data_inner_participants_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


