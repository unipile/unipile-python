# ParticipantRoleUpdated


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | ID of the participant whose role was updated. | 
**reason** | **str** | The type of role change applied to the participant. | 

## Example

```python
from unipile.models.participant_role_updated import ParticipantRoleUpdated

# TODO update the JSON string below
json = "{}"
# create an instance of ParticipantRoleUpdated from a JSON string
participant_role_updated_instance = ParticipantRoleUpdated.from_json(json)
# print the JSON string representation of the object
print(ParticipantRoleUpdated.to_json())

# convert the object into a dict
participant_role_updated_dict = participant_role_updated_instance.to_dict()
# create an instance of ParticipantRoleUpdated from a dict
participant_role_updated_from_dict = ParticipantRoleUpdated.from_dict(participant_role_updated_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


