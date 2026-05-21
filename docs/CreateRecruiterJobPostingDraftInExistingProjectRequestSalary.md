# CreateRecruiterJobPostingDraftInExistingProjectRequestSalary

The base salary for the job.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency** | **str** |  | 
**pay_frequency** | **str** | The frequency at which the compensation is paid. | 
**min** | **float** | The minimum in the compensation range. | 
**max** | **float** | The maximum in the compensation range. | 

## Example

```python
from unipile.models.create_recruiter_job_posting_draft_in_existing_project_request_salary import CreateRecruiterJobPostingDraftInExistingProjectRequestSalary

# TODO update the JSON string below
json = "{}"
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequestSalary from a JSON string
create_recruiter_job_posting_draft_in_existing_project_request_salary_instance = CreateRecruiterJobPostingDraftInExistingProjectRequestSalary.from_json(json)
# print the JSON string representation of the object
print(CreateRecruiterJobPostingDraftInExistingProjectRequestSalary.to_json())

# convert the object into a dict
create_recruiter_job_posting_draft_in_existing_project_request_salary_dict = create_recruiter_job_posting_draft_in_existing_project_request_salary_instance.to_dict()
# create an instance of CreateRecruiterJobPostingDraftInExistingProjectRequestSalary from a dict
create_recruiter_job_posting_draft_in_existing_project_request_salary_from_dict = CreateRecruiterJobPostingDraftInExistingProjectRequestSalary.from_dict(create_recruiter_job_posting_draft_in_existing_project_request_salary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


