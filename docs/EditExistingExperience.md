# EditExistingExperience


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**notify_network** | **bool** | Notify the network about the experience. Turn on to notify your network of key profile changes (such as new job) and work anniversaries. Updates can take up to 2 hours.  | [optional] [default to False]
**job_title** | [**EditExistingExperienceJobTitle**](EditExistingExperienceJobTitle.md) |  | [optional] 
**employment_type** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;EMPLOYMENT_TYPE&#x60; type to find out the possible values. Employment type of the experience. | [optional] 
**company** | [**EditExistingExperienceCompany**](EditExistingExperienceCompany.md) |  | [optional] 
**location** | [**EditExistingExperienceLocation**](EditExistingExperienceLocation.md) |  | [optional] 
**workplace_type** | **str** | The workplace type. Ex: Remote, Hybrid, On-site | [optional] 
**start_date** | [**CreateNewExperienceStartDate**](CreateNewExperienceStartDate.md) |  | [optional] 
**end_date** | [**CreateNewExperienceEndDate**](CreateNewExperienceEndDate.md) |  | [optional] 
**description** | **str** | Description of the experience. List your major duties and successes, highlighting specific projects. | [optional] 
**source_of_hire** | **str** | Where did you find this job? This information will be used to improve LinkedIn’s job search experience. | [optional] 
**skills** | [**List[CreateNewExperienceSkillsInner]**](CreateNewExperienceSkillsInner.md) | List of skills. We recommend adding your top 5 used in this role. They’ll also appear in your profile Skills section. | [optional] 
**media** | [**CreateNewExperienceMedia**](CreateNewExperienceMedia.md) |  | [optional] 
**operation** | **str** |  | 
**id** | **str** | ID of the experience to edit. | 

## Example

```python
from unipile.models.edit_existing_experience import EditExistingExperience

# TODO update the JSON string below
json = "{}"
# create an instance of EditExistingExperience from a JSON string
edit_existing_experience_instance = EditExistingExperience.from_json(json)
# print the JSON string representation of the object
print(EditExistingExperience.to_json())

# convert the object into a dict
edit_existing_experience_dict = edit_existing_experience_instance.to_dict()
# create an instance of EditExistingExperience from a dict
edit_existing_experience_from_dict = EditExistingExperience.from_dict(edit_existing_experience_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


