# LinkedIn1RecruitingProfileNotesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**project_id** | **str** | The ID of the project where the note was added. | [optional] 
**content** | **str** | The text content of the note. | 
**last_modified_at** | **str** | The time at which the note was last modified. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**author** | [**LinkedIn1InterestsTopVoicesInner**](LinkedIn1InterestsTopVoicesInner.md) |  | 
**comments** | [**List[LinkedIn1RecruitingProfileNotesInnerCommentsInner]**](LinkedIn1RecruitingProfileNotesInnerCommentsInner.md) | A list of comments published on this note. | 

## Example

```python
from unipile.models.linked_in1_recruiting_profile_notes_inner import LinkedIn1RecruitingProfileNotesInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1RecruitingProfileNotesInner from a JSON string
linked_in1_recruiting_profile_notes_inner_instance = LinkedIn1RecruitingProfileNotesInner.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1RecruitingProfileNotesInner.to_json())

# convert the object into a dict
linked_in1_recruiting_profile_notes_inner_dict = linked_in1_recruiting_profile_notes_inner_instance.to_dict()
# create an instance of LinkedIn1RecruitingProfileNotesInner from a dict
linked_in1_recruiting_profile_notes_inner_from_dict = LinkedIn1RecruitingProfileNotesInner.from_dict(linked_in1_recruiting_profile_notes_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


