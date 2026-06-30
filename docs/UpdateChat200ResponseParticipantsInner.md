# UpdateChat200ResponseParticipantsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**user** | [**GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender**](GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender.md) |  | 
**is_self** | **bool** | Is the current user the participant. | 
**is_admin** | **bool** | Is the participant an admin of the group. | 

## Example

```python
from unipile.models.update_chat200_response_participants_inner import UpdateChat200ResponseParticipantsInner

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateChat200ResponseParticipantsInner from a JSON string
update_chat200_response_participants_inner_instance = UpdateChat200ResponseParticipantsInner.from_json(json)
# print the JSON string representation of the object
print(UpdateChat200ResponseParticipantsInner.to_json())

# convert the object into a dict
update_chat200_response_participants_inner_dict = update_chat200_response_participants_inner_instance.to_dict()
# create an instance of UpdateChat200ResponseParticipantsInner from a dict
update_chat200_response_participants_inner_from_dict = UpdateChat200ResponseParticipantsInner.from_dict(update_chat200_response_participants_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


