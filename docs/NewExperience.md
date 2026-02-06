# NewExperience


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**notify_network** | **bool** | Notify the network about the experience. Turn on to notify your network of key profile changes (such as new job) and work anniversaries. Updates can take up to 2 hours.  | [optional] [default to False]
**job_title** | [**NewExperienceJobTitle**](NewExperienceJobTitle.md) |  | [optional] 
**employment_type** | **str** |  | [optional] 
**company** | [**NewExperienceCompany**](NewExperienceCompany.md) |  | [optional] 
**location** | [**NewExperienceLocation**](NewExperienceLocation.md) |  | [optional] 
**workplace_type** | **str** | The workplace type. Ex: Remote, Hybrid, On-site | [optional] 
**start_date** | [**NewExperienceStartDate**](NewExperienceStartDate.md) |  | 
**end_date** | [**NewExperienceEndDate**](NewExperienceEndDate.md) |  | [optional] 
**description** | **str** | Description of the experience. List your major duties and successes, highlighting specific projects. | [optional] 
**source_of_hire** | **str** | Where did you find this job? This information will be used to improve LinkedIn’s job search experience. | [optional] 
**skills** | [**List[NewExperienceSkillsInner]**](NewExperienceSkillsInner.md) | List of skills. We recommend adding your top 5 used in this role. They’ll also appear in your profile Skills section. | [optional] 
**attachment** | [**NewExperienceAttachment**](NewExperienceAttachment.md) |  | [optional] 
**attachment_title** | **str** | Title of the attachment. | [optional] 
**attachment_description** | **str** | Description of the attachment. | [optional] 

## Example

```python
from unipile.models.new_experience import NewExperience

# TODO update the JSON string below
json = "{}"
# create an instance of NewExperience from a JSON string
new_experience_instance = NewExperience.from_json(json)
# print the JSON string representation of the object
print(NewExperience.to_json())

# convert the object into a dict
new_experience_dict = new_experience_instance.to_dict()
# create an instance of NewExperience from a dict
new_experience_from_dict = NewExperience.from_dict(new_experience_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


