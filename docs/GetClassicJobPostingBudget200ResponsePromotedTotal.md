# GetClassicJobPostingBudget200ResponsePromotedTotal

The total Budget.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**min** | **float** | The minimum Budget amount to be spent. | 
**max** | **float** | The maximum Budget amount to be spent. | 
**recommended** | **float** | The recommended Budget amount to be spent. | 
**promoted_plus_recommended** | **float** | The recommended Budget amount to be spent in Promoted plus mode (AI powered candidates filtering). | 

## Example

```python
from unipile.models.get_classic_job_posting_budget200_response_promoted_total import GetClassicJobPostingBudget200ResponsePromotedTotal

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicJobPostingBudget200ResponsePromotedTotal from a JSON string
get_classic_job_posting_budget200_response_promoted_total_instance = GetClassicJobPostingBudget200ResponsePromotedTotal.from_json(json)
# print the JSON string representation of the object
print(GetClassicJobPostingBudget200ResponsePromotedTotal.to_json())

# convert the object into a dict
get_classic_job_posting_budget200_response_promoted_total_dict = get_classic_job_posting_budget200_response_promoted_total_instance.to_dict()
# create an instance of GetClassicJobPostingBudget200ResponsePromotedTotal from a dict
get_classic_job_posting_budget200_response_promoted_total_from_dict = GetClassicJobPostingBudget200ResponsePromotedTotal.from_dict(get_classic_job_posting_budget200_response_promoted_total_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


