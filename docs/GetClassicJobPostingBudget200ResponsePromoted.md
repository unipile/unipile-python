# GetClassicJobPostingBudget200ResponsePromoted

Promoted mode.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency** | **str** | The Budget currency. | 
**daily** | [**GetClassicJobPostingBudget200ResponsePromotedDaily**](GetClassicJobPostingBudget200ResponsePromotedDaily.md) |  | 
**total** | [**GetClassicJobPostingBudget200ResponsePromotedTotal**](GetClassicJobPostingBudget200ResponsePromotedTotal.md) |  | 
**estimated_daily_applicants_count** | **float** | The estimated number of applicants per day. | 

## Example

```python
from unipile.models.get_classic_job_posting_budget200_response_promoted import GetClassicJobPostingBudget200ResponsePromoted

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicJobPostingBudget200ResponsePromoted from a JSON string
get_classic_job_posting_budget200_response_promoted_instance = GetClassicJobPostingBudget200ResponsePromoted.from_json(json)
# print the JSON string representation of the object
print(GetClassicJobPostingBudget200ResponsePromoted.to_json())

# convert the object into a dict
get_classic_job_posting_budget200_response_promoted_dict = get_classic_job_posting_budget200_response_promoted_instance.to_dict()
# create an instance of GetClassicJobPostingBudget200ResponsePromoted from a dict
get_classic_job_posting_budget200_response_promoted_from_dict = GetClassicJobPostingBudget200ResponsePromoted.from_dict(get_classic_job_posting_budget200_response_promoted_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


