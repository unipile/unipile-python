# GetRecruiterJobPostingList200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**id** | **str** | The ID of the Job posting. | 
**project_id** | **str** | The ID of the project associated with the Job posting. | 
**title** | **str** | The title of the Job posting. | 
**company** | **str** | The company on whose behalf the Job posting was published. | 
**location** | **str** | The location of the Job posting. | 
**state** | **str** | The current state of the Job posting. | 
**applications_count** | **float** | The number of applications for this Job posting. | 
**views_count** | **float** | The number of visits to this Job posting. | 

## Example

```python
from unipile.models.get_recruiter_job_posting_list200_response_data_inner import GetRecruiterJobPostingList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterJobPostingList200ResponseDataInner from a JSON string
get_recruiter_job_posting_list200_response_data_inner_instance = GetRecruiterJobPostingList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterJobPostingList200ResponseDataInner.to_json())

# convert the object into a dict
get_recruiter_job_posting_list200_response_data_inner_dict = get_recruiter_job_posting_list200_response_data_inner_instance.to_dict()
# create an instance of GetRecruiterJobPostingList200ResponseDataInner from a dict
get_recruiter_job_posting_list200_response_data_inner_from_dict = GetRecruiterJobPostingList200ResponseDataInner.from_dict(get_recruiter_job_posting_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


