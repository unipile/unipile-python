# GetRecruiterJobPostingByProjectId200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**id** | **str** | The budget allocated to the Job posting. | 
**project_id** | **str** | The budget allocated to the Job posting. | 
**title** | **str** | The budget allocated to the Job posting. | 
**company** | [**GetRecruiterJobPostingByProjectId200ResponseCompany**](GetRecruiterJobPostingByProjectId200ResponseCompany.md) |  | 
**location** | **str** | The budget allocated to the Job posting. | 
**state** | **str** | The budget allocated to the Job posting. | 
**workplace_type** | **str** | The budget allocated to the Job posting. | 
**industries** | **List[Optional[str]]** | The budget allocated to the Job posting. | 
**job_functions** | **List[Optional[str]]** | The job functions associated with the Job posting. | 
**employment_status** | **str** | The employment status of the Job posting. | 
**experience_level** | **str** | The required level of experience of the Job posting. | 
**published_at** | **str** | The date on which the Job posting was published. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**expires_at** | **str** | The date on which the Job posting will expire. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**closed_at** | **str** | The date on which the Job posting was closed. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**description** | **str** | The description of the Job posting. | 
**views_count** | **float** | The number of visits to this Job posting. | 
**applications_count** | **float** | The number of applications for this Job posting. | 
**company_apply_url** | **str** | The application form URL of the company that published the Job posting. | [optional] 
**tracking_pixel_url** | **str** | The tracking pixel URL of the company that published the Job posting. | [optional] 
**screening_questions** | [**List[GetRecruiterJobPostingByProjectId200ResponseScreeningQuestionsInner]**](GetRecruiterJobPostingByProjectId200ResponseScreeningQuestionsInner.md) | The screening questions of the Job posting. | [optional] 
**hiring_team** | [**List[GetRecruiterJobPostingByProjectId200ResponseHiringTeamInner]**](GetRecruiterJobPostingByProjectId200ResponseHiringTeamInner.md) | A list of hiring team members for the Job posting. | 

## Example

```python
from unipile.models.get_recruiter_job_posting_by_project_id200_response import GetRecruiterJobPostingByProjectId200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterJobPostingByProjectId200Response from a JSON string
get_recruiter_job_posting_by_project_id200_response_instance = GetRecruiterJobPostingByProjectId200Response.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterJobPostingByProjectId200Response.to_json())

# convert the object into a dict
get_recruiter_job_posting_by_project_id200_response_dict = get_recruiter_job_posting_by_project_id200_response_instance.to_dict()
# create an instance of GetRecruiterJobPostingByProjectId200Response from a dict
get_recruiter_job_posting_by_project_id200_response_from_dict = GetRecruiterJobPostingByProjectId200Response.from_dict(get_recruiter_job_posting_by_project_id200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


