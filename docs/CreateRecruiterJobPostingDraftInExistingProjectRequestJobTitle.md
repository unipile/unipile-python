# CreateRecruiterJobPostingDraftInExistingProjectRequestJobTitle

The title of the job.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_TITLE&#x60; type to find out the possible values. | 
**name** | **str** | The name of the job. | 

## Example

```python
from unipile.models.create_recruiter_job_posting_draft_in_existing_project_request_job_title import CreateRecruiterJobPostingDraftInExistingProjectRequestJobTitle

# TODO update the JSON string below
json = "{}"
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequestJobTitle from a JSON string
create_recruiter_job_posting_draft_in_existing_project_request_job_title_instance = CreateRecruiterJobPostingDraftInExistingProjectRequestJobTitle.from_json(json)
# print the JSON string representation of the object
print(CreateRecruiterJobPostingDraftInExistingProjectRequestJobTitle.to_json())

# convert the object into a dict
create_recruiter_job_posting_draft_in_existing_project_request_job_title_dict = create_recruiter_job_posting_draft_in_existing_project_request_job_title_instance.to_dict()
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequestJobTitle from a dict
create_recruiter_job_posting_draft_in_existing_project_request_job_title_from_dict = CreateRecruiterJobPostingDraftInExistingProjectRequestJobTitle.from_dict(create_recruiter_job_posting_draft_in_existing_project_request_job_title_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


