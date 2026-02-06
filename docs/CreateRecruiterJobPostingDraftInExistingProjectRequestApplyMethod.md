# CreateRecruiterJobPostingDraftInExistingProjectRequestApplyMethod

The apply method, either `linkedin` or `external`.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**method** | **str** |  | 
**notification_email** | **str** | An email address to get updates about applicants. | 
**resume_required** | **bool** | Whether to require a resume from the applicants. | 
**website_url** | **str** | The website on which applications should be made. | 

## Example

```python
from unipile.models.create_recruiter_job_posting_draft_in_existing_project_request_apply_method import CreateRecruiterJobPostingDraftInExistingProjectRequestApplyMethod

# TODO update the JSON string below
json = "{}"
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequestApplyMethod from a JSON string
create_recruiter_job_posting_draft_in_existing_project_request_apply_method_instance = CreateRecruiterJobPostingDraftInExistingProjectRequestApplyMethod.from_json(json)
# print the JSON string representation of the object
print(CreateRecruiterJobPostingDraftInExistingProjectRequestApplyMethod.to_json())

# convert the object into a dict
create_recruiter_job_posting_draft_in_existing_project_request_apply_method_dict = create_recruiter_job_posting_draft_in_existing_project_request_apply_method_instance.to_dict()
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequestApplyMethod from a dict
create_recruiter_job_posting_draft_in_existing_project_request_apply_method_from_dict = CreateRecruiterJobPostingDraftInExistingProjectRequestApplyMethod.from_dict(create_recruiter_job_posting_draft_in_existing_project_request_apply_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


