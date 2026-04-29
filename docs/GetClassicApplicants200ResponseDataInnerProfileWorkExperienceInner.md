# GetClassicApplicants200ResponseDataInnerProfileWorkExperienceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**company** | [**LinkedInCertificationsInnerOrganization**](LinkedInCertificationsInnerOrganization.md) |  | 
**title** | **str** | The position name in the experience. | 
**started_on** | **str** | The start date of the experience in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | The end date of the experience in MM/DD/YYYY format. | [optional] 
**location** | **str** | The location of the experience. | [optional] 
**description** | **str** | The description of the experience. | [optional] 
**employment_type** | **str** | The employment type of the experience. | [optional] 

## Example

```python
from unipile.models.get_classic_applicants200_response_data_inner_profile_work_experience_inner import GetClassicApplicants200ResponseDataInnerProfileWorkExperienceInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicApplicants200ResponseDataInnerProfileWorkExperienceInner from a JSON string
get_classic_applicants200_response_data_inner_profile_work_experience_inner_instance = GetClassicApplicants200ResponseDataInnerProfileWorkExperienceInner.from_json(json)
# print the JSON string representation of the object
print(GetClassicApplicants200ResponseDataInnerProfileWorkExperienceInner.to_json())

# convert the object into a dict
get_classic_applicants200_response_data_inner_profile_work_experience_inner_dict = get_classic_applicants200_response_data_inner_profile_work_experience_inner_instance.to_dict()
# create an instance of GetClassicApplicants200ResponseDataInnerProfileWorkExperienceInner from a dict
get_classic_applicants200_response_data_inner_profile_work_experience_inner_from_dict = GetClassicApplicants200ResponseDataInnerProfileWorkExperienceInner.from_dict(get_classic_applicants200_response_data_inner_profile_work_experience_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


