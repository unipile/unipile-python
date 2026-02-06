# GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInnerCompany


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the company. | [optional] 
**id** | **str** | Unique identifier of the company. | 
**public_identifier** | **str** | Public identifier of the company. | [optional] 
**picture_url** | **str** | Public url to the profile picture of the company. | [optional] 
**profile_url** | **str** | Public url to the profile of the company. | [optional] 
**industries** | **List[Optional[str]]** | Industry types of the company. | [optional] 

## Example

```python
from unipile.models.get_user_profile200_response_specifics_all_of_any_of_experience_inner_company import GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInnerCompany

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInnerCompany from a JSON string
get_user_profile200_response_specifics_all_of_any_of_experience_inner_company_instance = GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInnerCompany.from_json(json)
# print the JSON string representation of the object
print(GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInnerCompany.to_json())

# convert the object into a dict
get_user_profile200_response_specifics_all_of_any_of_experience_inner_company_dict = get_user_profile200_response_specifics_all_of_any_of_experience_inner_company_instance.to_dict()
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInnerCompany from a dict
get_user_profile200_response_specifics_all_of_any_of_experience_inner_company_from_dict = GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInnerCompany.from_dict(get_user_profile200_response_specifics_all_of_any_of_experience_inner_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


