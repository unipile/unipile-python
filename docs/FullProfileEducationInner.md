# FullProfileEducationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Id of the education entry. | [optional] 
**school** | [**GetUserProfile200ResponseSpecificsAllOfAnyOfEducationInnerSchool**](GetUserProfile200ResponseSpecificsAllOfAnyOfEducationInnerSchool.md) |  | 
**degree** | **str** | Name of the degree. | [optional] 
**description** | **str** | Description of the education. | [optional] 
**activities** | **str** | Activities carried out during education. | [optional] 
**skills** | **List[str]** | Skills acquired through training. | [optional] 
**skills_preview** | **str** | Insight of the skills acquired through training. | [optional] 
**grade** | **str** | Reached academic level of the education. | [optional] 
**fields_of_study** | **List[str]** | Fields of study of the education. | [optional] 
**started_on** | **str** | Start date of the education in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | End date of the education in MM/DD/YYYY format. | [optional] 

## Example

```python
from unipile.models.full_profile_education_inner import FullProfileEducationInner

# TODO update the JSON string below
json = "{}"
# create an instance of FullProfileEducationInner from a JSON string
full_profile_education_inner_instance = FullProfileEducationInner.from_json(json)
# print the JSON string representation of the object
print(FullProfileEducationInner.to_json())

# convert the object into a dict
full_profile_education_inner_dict = full_profile_education_inner_instance.to_dict()
# create an instance of FullProfileEducationInner from a dict
full_profile_education_inner_from_dict = FullProfileEducationInner.from_dict(full_profile_education_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


