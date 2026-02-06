# PerformRecruiterPeopleSearchFromTalentPoolRequestSkillsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The skill name. | 
**id** | **str** |  | [optional] 
**priority** | **str** | Whether the user can, must or shouldn&#39;t have the value.    Native filter : Priority    | [optional] [default to 'CAN_HAVE']

## Example

```python
from unipile.models.perform_recruiter_people_search_from_talent_pool_request_skills_inner import PerformRecruiterPeopleSearchFromTalentPoolRequestSkillsInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestSkillsInner from a JSON string
perform_recruiter_people_search_from_talent_pool_request_skills_inner_instance = PerformRecruiterPeopleSearchFromTalentPoolRequestSkillsInner.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchFromTalentPoolRequestSkillsInner.to_json())

# convert the object into a dict
perform_recruiter_people_search_from_talent_pool_request_skills_inner_dict = perform_recruiter_people_search_from_talent_pool_request_skills_inner_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestSkillsInner from a dict
perform_recruiter_people_search_from_talent_pool_request_skills_inner_from_dict = PerformRecruiterPeopleSearchFromTalentPoolRequestSkillsInner.from_dict(perform_recruiter_people_search_from_talent_pool_request_skills_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


