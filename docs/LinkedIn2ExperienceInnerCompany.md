# LinkedIn2ExperienceInnerCompany


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the company. | [optional] 
**id** | **str** | Unique identifier of the company. | 
**public_identifier** | **str** | Public identifier of the company. | [optional] 
**picture_url** | **str** | Public url to the profile picture of the company. | [optional] 
**profile_url** | **str** | Public url to the profile of the company. | [optional] 
**industries** | **List[Optional[str]]** | Industry types of the company. | [optional] 
**headcount_range** | [**LinkedIn2ExperienceInnerCompanyHeadcountRange**](LinkedIn2ExperienceInnerCompanyHeadcountRange.md) |  | [optional] 

## Example

```python
from unipile.models.linked_in2_experience_inner_company import LinkedIn2ExperienceInnerCompany

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn2ExperienceInnerCompany from a JSON string
linked_in2_experience_inner_company_instance = LinkedIn2ExperienceInnerCompany.from_json(json)
# print the JSON string representation of the object
print(LinkedIn2ExperienceInnerCompany.to_json())

# convert the object into a dict
linked_in2_experience_inner_company_dict = linked_in2_experience_inner_company_instance.to_dict()
# create an instance of LinkedIn2ExperienceInnerCompany from a dict
linked_in2_experience_inner_company_from_dict = LinkedIn2ExperienceInnerCompany.from_dict(linked_in2_experience_inner_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


