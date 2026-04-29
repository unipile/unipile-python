# LinkedInExperienceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Id of the work experience entry. | [optional] 
**company** | [**LinkedInExperienceInnerCompany**](LinkedInExperienceInnerCompany.md) |  | 
**job_title** | **str** | Job title of the experience. | 
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
from unipile.models.linked_in_experience_inner import LinkedInExperienceInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInExperienceInner from a JSON string
linked_in_experience_inner_instance = LinkedInExperienceInner.from_json(json)
# print the JSON string representation of the object
print(LinkedInExperienceInner.to_json())

# convert the object into a dict
linked_in_experience_inner_dict = linked_in_experience_inner_instance.to_dict()
# create an instance of LinkedInExperienceInner from a dict
linked_in_experience_inner_from_dict = LinkedInExperienceInner.from_dict(linked_in_experience_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


