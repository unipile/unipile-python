# PartialProfileWorkExperienceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Id of the work experience entry. | [optional] 
**company** | [**LinkedInCertificationsInnerOrganization**](LinkedInCertificationsInnerOrganization.md) |  | 
**job_title** | **str** | Job title of the experience. | 
**started_on** | **str** | Start date of the experience in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | End date of the experience in MM/DD/YYYY format. | [optional] 
**location** | **str** | Location of the experience. | [optional] 
**description** | **str** | Description of the experience. | [optional] 
**employment_type** | **str** | Employment type of the experience. | [optional] 
**workplace_type** | **str** | Workplace type of the experience. | [optional] 
**skills** | **List[str]** | Skills acquired with experience. | [optional] 
**skills_preview** | **str** | Insight of the skills acquired with experience. | [optional] 

## Example

```python
from unipile.models.partial_profile_work_experience_inner import PartialProfileWorkExperienceInner

# TODO update the JSON string below
json = "{}"
# create an instance of PartialProfileWorkExperienceInner from a JSON string
partial_profile_work_experience_inner_instance = PartialProfileWorkExperienceInner.from_json(json)
# print the JSON string representation of the object
print(PartialProfileWorkExperienceInner.to_json())

# convert the object into a dict
partial_profile_work_experience_inner_dict = partial_profile_work_experience_inner_instance.to_dict()
# create an instance of PartialProfileWorkExperienceInner from a dict
partial_profile_work_experience_inner_from_dict = PartialProfileWorkExperienceInner.from_dict(partial_profile_work_experience_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


