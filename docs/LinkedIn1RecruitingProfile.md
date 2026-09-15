# LinkedIn1RecruitingProfile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**events** | [**List[LinkedIn1RecruitingProfileEventsInner]**](LinkedIn1RecruitingProfileEventsInner.md) | A list of events related to the user. | [optional] 
**notes** | [**List[LinkedIn1RecruitingProfileNotesInner]**](LinkedIn1RecruitingProfileNotesInner.md) | A list of notes about the user. | 
**tags** | [**List[LinkedIn1RecruitingProfileTagsInner]**](LinkedIn1RecruitingProfileTagsInner.md) | A list of tags about the user. | 

## Example

```python
from unipile.models.linked_in1_recruiting_profile import LinkedIn1RecruitingProfile

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1RecruitingProfile from a JSON string
linked_in1_recruiting_profile_instance = LinkedIn1RecruitingProfile.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1RecruitingProfile.to_json())

# convert the object into a dict
linked_in1_recruiting_profile_dict = linked_in1_recruiting_profile_instance.to_dict()
# create an instance of LinkedIn1RecruitingProfile from a dict
linked_in1_recruiting_profile_from_dict = LinkedIn1RecruitingProfile.from_dict(linked_in1_recruiting_profile_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


