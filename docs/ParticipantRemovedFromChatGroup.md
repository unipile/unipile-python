# ParticipantRemovedFromChatGroup


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | ID of the participant who left or was removed from the group. | [optional] 
**user_name** | **str** | Name of the participant who left or was removed from the group. | [optional] 
**reason** | **str** | Specifies whether the participant left voluntarily or was removed by an admin. | 

## Example

```python
from unipile.models.participant_removed_from_chat_group import ParticipantRemovedFromChatGroup

# TODO update the JSON string below
json = "{}"
# create an instance of ParticipantRemovedFromChatGroup from a JSON string
participant_removed_from_chat_group_instance = ParticipantRemovedFromChatGroup.from_json(json)
# print the JSON string representation of the object
print(ParticipantRemovedFromChatGroup.to_json())

# convert the object into a dict
participant_removed_from_chat_group_dict = participant_removed_from_chat_group_instance.to_dict()
# create an instance of ParticipantRemovedFromChatGroup from a dict
participant_removed_from_chat_group_from_dict = ParticipantRemovedFromChatGroup.from_dict(participant_removed_from_chat_group_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


