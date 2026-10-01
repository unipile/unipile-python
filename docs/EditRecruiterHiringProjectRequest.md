# EditRecruiterHiringProjectRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The name of the project. | [optional] 
**visibility** | **str** | The vibility of the project. | [optional] 
**description** | **str** | The description of the project. | [optional] 
**company** | [**CreateRecruiterHiringProjectRequestCompany**](CreateRecruiterHiringProjectRequestCompany.md) |  | [optional] 
**job_title** | [**CreateRecruiterHiringProjectRequestJobTitle**](CreateRecruiterHiringProjectRequestJobTitle.md) |  | [optional] 
**location** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;LOCATION&#x60; type to find out the possible values. | [optional] 
**seniority_level** | **str** | The level of experience of the project. | [optional] 
**employment_status** | **str** | The employment status of the project. | [optional] 
**industry** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;INDUSTRY&#x60; type to find out the possible values. The company industries related to the project. | [optional] 
**job_function** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getrecruitersearchparameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_FUNCTION&#x60; type to find out the possible values. The job functions of the project. | [optional] 

## Example

```python
from unipile.models.edit_recruiter_hiring_project_request import EditRecruiterHiringProjectRequest

# TODO update the JSON string below
json = "{}"
# create an instance of EditRecruiterHiringProjectRequest from a JSON string
edit_recruiter_hiring_project_request_instance = EditRecruiterHiringProjectRequest.from_json(json)
# print the JSON string representation of the object
print(EditRecruiterHiringProjectRequest.to_json())

# convert the object into a dict
edit_recruiter_hiring_project_request_dict = edit_recruiter_hiring_project_request_instance.to_dict()
# create an instance of EditRecruiterHiringProjectRequest from a dict
edit_recruiter_hiring_project_request_from_dict = EditRecruiterHiringProjectRequest.from_dict(edit_recruiter_hiring_project_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


