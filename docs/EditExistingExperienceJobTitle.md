# EditExistingExperienceJobTitle

Job title of the experience.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_TITLE&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.edit_existing_experience_job_title import EditExistingExperienceJobTitle

# TODO update the JSON string below
json = "{}"
# create an instance of EditExistingExperienceJobTitle from a JSON string
edit_existing_experience_job_title_instance = EditExistingExperienceJobTitle.from_json(json)
# print the JSON string representation of the object
print(EditExistingExperienceJobTitle.to_json())

# convert the object into a dict
edit_existing_experience_job_title_dict = edit_existing_experience_job_title_instance.to_dict()
# create an instance of EditExistingExperienceJobTitle from a dict
edit_existing_experience_job_title_from_dict = EditExistingExperienceJobTitle.from_dict(edit_existing_experience_job_title_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


