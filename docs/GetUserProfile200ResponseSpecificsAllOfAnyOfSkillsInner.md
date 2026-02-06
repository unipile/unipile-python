# GetUserProfile200ResponseSpecificsAllOfAnyOfSkillsInner


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
from unipile.models.get_user_profile200_response_specifics_all_of_any_of_skills_inner import GetUserProfile200ResponseSpecificsAllOfAnyOfSkillsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfSkillsInner from a JSON string
get_user_profile200_response_specifics_all_of_any_of_skills_inner_instance = GetUserProfile200ResponseSpecificsAllOfAnyOfSkillsInner.from_json(json)
# print the JSON string representation of the object
print(GetUserProfile200ResponseSpecificsAllOfAnyOfSkillsInner.to_json())

# convert the object into a dict
get_user_profile200_response_specifics_all_of_any_of_skills_inner_dict = get_user_profile200_response_specifics_all_of_any_of_skills_inner_instance.to_dict()
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfSkillsInner from a dict
get_user_profile200_response_specifics_all_of_any_of_skills_inner_from_dict = GetUserProfile200ResponseSpecificsAllOfAnyOfSkillsInner.from_dict(get_user_profile200_response_specifics_all_of_any_of_skills_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


