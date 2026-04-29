# LinkedInRecruitingProfile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**events** | [**List[LinkedInRecruitingProfileEventsInner]**](LinkedInRecruitingProfileEventsInner.md) | A list of events related to the user. | [optional] 
**notes** | [**List[LinkedInRecruitingProfileNotesInner]**](LinkedInRecruitingProfileNotesInner.md) | A list of notes about the user. | 
**tags** | [**List[LinkedInRecruitingProfileTagsInner]**](LinkedInRecruitingProfileTagsInner.md) | A list of tags about the user. | 

## Example

```python
from unipile.models.linked_in_recruiting_profile import LinkedInRecruitingProfile

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInRecruitingProfile from a JSON string
linked_in_recruiting_profile_instance = LinkedInRecruitingProfile.from_json(json)
# print the JSON string representation of the object
print(LinkedInRecruitingProfile.to_json())

# convert the object into a dict
linked_in_recruiting_profile_dict = linked_in_recruiting_profile_instance.to_dict()
# create an instance of LinkedInRecruitingProfile from a dict
linked_in_recruiting_profile_from_dict = LinkedInRecruitingProfile.from_dict(linked_in_recruiting_profile_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


