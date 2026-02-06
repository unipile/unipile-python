# CreateRecruiterJobPostingDraftInExistingProjectRequestRejectionSettings

The settings for automated rejection system.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**send_rejection_notification** | **bool** | Whether rejected applicants should receive a notification. | [optional] [default to True]
**rejection_template** | **str** | The textual content that will be sent to rejected applicants. | [optional] 
**reject_unqualified_applicants** | **bool** | Whether to archive applicants who don’t meet any must-have qualifications. | [optional] [default to True]
**reject_out_of_country_applicants** | **bool** | Whether to archive applicants who live outside the country where the job is located. | [optional] [default to True]

## Example

```python
from unipile.models.create_recruiter_job_posting_draft_in_existing_project_request_rejection_settings import CreateRecruiterJobPostingDraftInExistingProjectRequestRejectionSettings

# TODO update the JSON string below
json = "{}"
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequestRejectionSettings from a JSON string
create_recruiter_job_posting_draft_in_existing_project_request_rejection_settings_instance = CreateRecruiterJobPostingDraftInExistingProjectRequestRejectionSettings.from_json(json)
# print the JSON string representation of the object
print(CreateRecruiterJobPostingDraftInExistingProjectRequestRejectionSettings.to_json())

# convert the object into a dict
create_recruiter_job_posting_draft_in_existing_project_request_rejection_settings_dict = create_recruiter_job_posting_draft_in_existing_project_request_rejection_settings_instance.to_dict()
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequestRejectionSettings from a dict
create_recruiter_job_posting_draft_in_existing_project_request_rejection_settings_from_dict = CreateRecruiterJobPostingDraftInExistingProjectRequestRejectionSettings.from_dict(create_recruiter_job_posting_draft_in_existing_project_request_rejection_settings_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


