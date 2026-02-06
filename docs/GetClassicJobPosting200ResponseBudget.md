# GetClassicJobPosting200ResponseBudget

The budget allocated to the Job posting.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total** | [**GetClassicJobPosting200ResponseBudgetTotal**](GetClassicJobPosting200ResponseBudgetTotal.md) |  | 
**daily** | [**GetClassicJobPosting200ResponseBudgetDaily**](GetClassicJobPosting200ResponseBudgetDaily.md) |  | 

## Example

```python
from unipile.models.get_classic_job_posting200_response_budget import GetClassicJobPosting200ResponseBudget

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicJobPosting200ResponseBudget from a JSON string
get_classic_job_posting200_response_budget_instance = GetClassicJobPosting200ResponseBudget.from_json(json)
# print the JSON string representation of the object
print(GetClassicJobPosting200ResponseBudget.to_json())

# convert the object into a dict
get_classic_job_posting200_response_budget_dict = get_classic_job_posting200_response_budget_instance.to_dict()
# create an instance of GetClassicJobPosting200ResponseBudget from a dict
get_classic_job_posting200_response_budget_from_dict = GetClassicJobPosting200ResponseBudget.from_dict(get_classic_job_posting200_response_budget_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


