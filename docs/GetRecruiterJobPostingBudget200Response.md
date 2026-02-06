# GetRecruiterJobPostingBudget200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**promoted** | [**GetRecruiterJobPostingBudget200ResponsePromoted**](GetRecruiterJobPostingBudget200ResponsePromoted.md) |  | 
**free** | [**GetRecruiterJobPostingBudget200ResponseFree**](GetRecruiterJobPostingBudget200ResponseFree.md) |  | 

## Example

```python
from unipile.models.get_recruiter_job_posting_budget200_response import GetRecruiterJobPostingBudget200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterJobPostingBudget200Response from a JSON string
get_recruiter_job_posting_budget200_response_instance = GetRecruiterJobPostingBudget200Response.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterJobPostingBudget200Response.to_json())

# convert the object into a dict
get_recruiter_job_posting_budget200_response_dict = get_recruiter_job_posting_budget200_response_instance.to_dict()
# create an instance of GetRecruiterJobPostingBudget200Response from a dict
get_recruiter_job_posting_budget200_response_from_dict = GetRecruiterJobPostingBudget200Response.from_dict(get_recruiter_job_posting_budget200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


