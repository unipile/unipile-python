# FullProfileSkillsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the skill. | 
**endorsement_count** | **float** | Number of people who endorsed the skill. | 

## Example

```python
from unipile.models.full_profile_skills_inner import FullProfileSkillsInner

# TODO update the JSON string below
json = "{}"
# create an instance of FullProfileSkillsInner from a JSON string
full_profile_skills_inner_instance = FullProfileSkillsInner.from_json(json)
# print the JSON string representation of the object
print(FullProfileSkillsInner.to_json())

# convert the object into a dict
full_profile_skills_inner_dict = full_profile_skills_inner_instance.to_dict()
# create an instance of FullProfileSkillsInner from a dict
full_profile_skills_inner_from_dict = FullProfileSkillsInner.from_dict(full_profile_skills_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


