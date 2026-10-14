# LinkedIn1SkillsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the skill. | 
**endorsement_count** | **float** | Number of people who endorsed the skill. | 
**endorsement_id** | **float** | Unique identifier to be used to endorse the skill. | [optional] 
**endorsed** | **bool** | Whether the viewer has endorsed the skill. | [optional] 
**insights** | **List[Optional[str]]** | Insights about the skill. | [optional] 

## Example

```python
from unipile.models.linked_in1_skills_inner import LinkedIn1SkillsInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1SkillsInner from a JSON string
linked_in1_skills_inner_instance = LinkedIn1SkillsInner.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1SkillsInner.to_json())

# convert the object into a dict
linked_in1_skills_inner_dict = linked_in1_skills_inner_instance.to_dict()
# create an instance of LinkedIn1SkillsInner from a dict
linked_in1_skills_inner_from_dict = LinkedIn1SkillsInner.from_dict(linked_in1_skills_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


