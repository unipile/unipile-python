# NewParticipantJoinedTheChatGroup


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**link** | **str** | The invitation link used to join the group. | [optional] 
**user_id** | **str** | ID of the participant who joined the group. | 

## Example

```python
from unipile.models.new_participant_joined_the_chat_group import NewParticipantJoinedTheChatGroup

# TODO update the JSON string below
json = "{}"
# create an instance of NewParticipantJoinedTheChatGroup from a JSON string
new_participant_joined_the_chat_group_instance = NewParticipantJoinedTheChatGroup.from_json(json)
# print the JSON string representation of the object
print(NewParticipantJoinedTheChatGroup.to_json())

# convert the object into a dict
new_participant_joined_the_chat_group_dict = new_participant_joined_the_chat_group_instance.to_dict()
# create an instance of NewParticipantJoinedTheChatGroup from a dict
new_participant_joined_the_chat_group_from_dict = NewParticipantJoinedTheChatGroup.from_dict(new_participant_joined_the_chat_group_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


