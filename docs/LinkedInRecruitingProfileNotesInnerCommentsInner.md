# LinkedInRecruitingProfileNotesInnerCommentsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content** | **str** | The text content of the comment. | 
**author** | [**LinkedInProjectsInnerContributorsInner**](LinkedInProjectsInnerContributorsInner.md) |  | 
**last_modified_at** | **str** | The time at which the comment was last modified. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 

## Example

```python
from unipile.models.linked_in_recruiting_profile_notes_inner_comments_inner import LinkedInRecruitingProfileNotesInnerCommentsInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInRecruitingProfileNotesInnerCommentsInner from a JSON string
linked_in_recruiting_profile_notes_inner_comments_inner_instance = LinkedInRecruitingProfileNotesInnerCommentsInner.from_json(json)
# print the JSON string representation of the object
print(LinkedInRecruitingProfileNotesInnerCommentsInner.to_json())

# convert the object into a dict
linked_in_recruiting_profile_notes_inner_comments_inner_dict = linked_in_recruiting_profile_notes_inner_comments_inner_instance.to_dict()
# create an instance of LinkedInRecruitingProfileNotesInnerCommentsInner from a dict
linked_in_recruiting_profile_notes_inner_comments_inner_from_dict = LinkedInRecruitingProfileNotesInnerCommentsInner.from_dict(linked_in_recruiting_profile_notes_inner_comments_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


