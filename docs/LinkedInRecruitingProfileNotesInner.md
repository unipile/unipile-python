# LinkedInRecruitingProfileNotesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**project_id** | **str** | The ID of the project where the note was added. | [optional] 
**content** | **str** | The text content of the note. | 
**last_modified_at** | **str** | The time at which the note was last modified. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**author** | [**LinkedInProjectsInnerContributorsInner**](LinkedInProjectsInnerContributorsInner.md) |  | 
**comments** | [**List[LinkedInRecruitingProfileNotesInnerCommentsInner]**](LinkedInRecruitingProfileNotesInnerCommentsInner.md) | A list of comments published on this note. | 

## Example

```python
from unipile.models.linked_in_recruiting_profile_notes_inner import LinkedInRecruitingProfileNotesInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInRecruitingProfileNotesInner from a JSON string
linked_in_recruiting_profile_notes_inner_instance = LinkedInRecruitingProfileNotesInner.from_json(json)
# print the JSON string representation of the object
print(LinkedInRecruitingProfileNotesInner.to_json())

# convert the object into a dict
linked_in_recruiting_profile_notes_inner_dict = linked_in_recruiting_profile_notes_inner_instance.to_dict()
# create an instance of LinkedInRecruitingProfileNotesInner from a dict
linked_in_recruiting_profile_notes_inner_from_dict = LinkedInRecruitingProfileNotesInner.from_dict(linked_in_recruiting_profile_notes_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


