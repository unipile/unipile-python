# CreateRecruiterJobPostingDraftInExistingProjectRequestAdditionalCompensation

Any additional compensation for the job.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency** | **str** |  | 
**pay_frequency** | **str** | The frequency at which the compensation is paid. | 
**min** | **float** | The minimum in the compensation range. | 
**max** | **float** | The maximum in the compensation range. | 

## Example

```python
from unipile.models.create_recruiter_job_posting_draft_in_existing_project_request_additional_compensation import CreateRecruiterJobPostingDraftInExistingProjectRequestAdditionalCompensation

# TODO update the JSON string below
json = "{}"
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequestAdditionalCompensation from a JSON string
create_recruiter_job_posting_draft_in_existing_project_request_additional_compensation_instance = CreateRecruiterJobPostingDraftInExistingProjectRequestAdditionalCompensation.from_json(json)
# print the JSON string representation of the object
print(CreateRecruiterJobPostingDraftInExistingProjectRequestAdditionalCompensation.to_json())

# convert the object into a dict
create_recruiter_job_posting_draft_in_existing_project_request_additional_compensation_dict = create_recruiter_job_posting_draft_in_existing_project_request_additional_compensation_instance.to_dict()
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequestAdditionalCompensation from a dict
create_recruiter_job_posting_draft_in_existing_project_request_additional_compensation_from_dict = CreateRecruiterJobPostingDraftInExistingProjectRequestAdditionalCompensation.from_dict(create_recruiter_job_posting_draft_in_existing_project_request_additional_compensation_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


