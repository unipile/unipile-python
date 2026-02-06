# GetRecruiterJobPostingBudget200ResponsePromoted


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency** | **str** | The Budget currency. | 
**daily** | [**GetRecruiterJobPostingBudget200ResponsePromotedDaily**](GetRecruiterJobPostingBudget200ResponsePromotedDaily.md) |  | 
**total** | [**GetRecruiterJobPostingBudget200ResponsePromotedDaily**](GetRecruiterJobPostingBudget200ResponsePromotedDaily.md) |  | 
**estimated_daily_applicants_count** | **float** | The estimated number of applicants per day. | 

## Example

```python
from unipile.models.get_recruiter_job_posting_budget200_response_promoted import GetRecruiterJobPostingBudget200ResponsePromoted

# TODO update the JSON string below
json = "{}"
# create an instance of GetRecruiterJobPostingBudget200ResponsePromoted from a JSON string
get_recruiter_job_posting_budget200_response_promoted_instance = GetRecruiterJobPostingBudget200ResponsePromoted.from_json(json)
# print the JSON string representation of the object
print(GetRecruiterJobPostingBudget200ResponsePromoted.to_json())

# convert the object into a dict
get_recruiter_job_posting_budget200_response_promoted_dict = get_recruiter_job_posting_budget200_response_promoted_instance.to_dict()
# create an instance of GetRecruiterJobPostingBudget200ResponsePromoted from a dict
get_recruiter_job_posting_budget200_response_promoted_from_dict = GetRecruiterJobPostingBudget200ResponsePromoted.from_dict(get_recruiter_job_posting_budget200_response_promoted_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


