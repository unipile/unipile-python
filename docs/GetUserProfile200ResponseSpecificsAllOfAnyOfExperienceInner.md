# GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Id of the work experience entry. | [optional] 
**company** | [**GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInnerCompany**](GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInnerCompany.md) |  | 
**title** | **str** | Position name in the experience. | 
**started_on** | **str** | Start date of the experience in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | End date of the experience in MM/DD/YYYY format. | [optional] 
**location** | **str** | Location of the experience. | [optional] 
**description** | **str** | Description of the experience. | [optional] 
**employment_type** | **str** | Employment type of the experience. | [optional] 
**workplace_type** | **str** | Workplace type of the experience. | [optional] 
**skills** | **List[Optional[str]]** | Skills acquired with experience. | [optional] 
**skills_preview** | **str** | Insight of the skills acquired with experience. | [optional] 

## Example

```python
from unipile.models.get_user_profile200_response_specifics_all_of_any_of_experience_inner import GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInner from a JSON string
get_user_profile200_response_specifics_all_of_any_of_experience_inner_instance = GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInner.from_json(json)
# print the JSON string representation of the object
print(GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInner.to_json())

# convert the object into a dict
get_user_profile200_response_specifics_all_of_any_of_experience_inner_dict = get_user_profile200_response_specifics_all_of_any_of_experience_inner_instance.to_dict()
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInner from a dict
get_user_profile200_response_specifics_all_of_any_of_experience_inner_from_dict = GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInner.from_dict(get_user_profile200_response_specifics_all_of_any_of_experience_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


