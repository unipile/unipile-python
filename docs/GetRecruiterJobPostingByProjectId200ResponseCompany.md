# GetRecruiterJobPostingByProjectId200ResponseCompany

The company on whose behalf the Job posting was published.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The text content of the message, when available. | 
**name** | **str** | The name of the company. | 
**public_picture_url** | **str** | A link to the picture of the company. | [optional] 
**profile_url** | **str** | A link to the public profile of the company. | [optional] 

## Example

```python
from unipile.models.get_recruiter_job_posting_by_project_id200_response_company import GetRecruiterJobPostingByProjectId200ResponseCompany

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterJobPostingByProjectId200ResponseCompany from a JSON string
get_recruiter_job_posting_by_project_id200_response_company_instance = GetRecruiterJobPostingByProjectId200ResponseCompany.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterJobPostingByProjectId200ResponseCompany.to_json())

# convert the object into a dict
get_recruiter_job_posting_by_project_id200_response_company_dict = get_recruiter_job_posting_by_project_id200_response_company_instance.to_dict()
# create an instance of GetRecruiterJobPostingByProjectId200ResponseCompany from a dict
get_recruiter_job_posting_by_project_id200_response_company_from_dict = GetRecruiterJobPostingByProjectId200ResponseCompany.from_dict(get_recruiter_job_posting_by_project_id200_response_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


