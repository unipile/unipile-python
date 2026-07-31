# LinkedIn1RecruitingProfileNotesInnerCommentsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content** | **str** | The text content of the comment. | 
**author** | [**LinkedIn1InterestsTopVoicesInner**](LinkedIn1InterestsTopVoicesInner.md) |  | 
**last_modified_at** | **str** | The time at which the comment was last modified. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 

## Example

```python
from unipile.models.linked_in1_recruiting_profile_notes_inner_comments_inner import LinkedIn1RecruitingProfileNotesInnerCommentsInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1RecruitingProfileNotesInnerCommentsInner from a JSON string
linked_in1_recruiting_profile_notes_inner_comments_inner_instance = LinkedIn1RecruitingProfileNotesInnerCommentsInner.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1RecruitingProfileNotesInnerCommentsInner.to_json())

# convert the object into a dict
linked_in1_recruiting_profile_notes_inner_comments_inner_dict = linked_in1_recruiting_profile_notes_inner_comments_inner_instance.to_dict()
# create an instance of LinkedIn1RecruitingProfileNotesInnerCommentsInner from a dict
linked_in1_recruiting_profile_notes_inner_comments_inner_from_dict = LinkedIn1RecruitingProfileNotesInnerCommentsInner.from_dict(linked_in1_recruiting_profile_notes_inner_comments_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


