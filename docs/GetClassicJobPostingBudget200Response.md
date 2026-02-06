# GetClassicJobPostingBudget200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**promoted** | [**GetClassicJobPostingBudget200ResponsePromoted**](GetClassicJobPostingBudget200ResponsePromoted.md) |  | 
**free** | [**GetClassicJobPostingBudget200ResponseFree**](GetClassicJobPostingBudget200ResponseFree.md) |  | 

## Example

```python
from unipile.models.get_classic_job_posting_budget200_response import GetClassicJobPostingBudget200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicJobPostingBudget200Response from a JSON string
get_classic_job_posting_budget200_response_instance = GetClassicJobPostingBudget200Response.from_json(json)
# print the JSON string representation of the object
print(GetClassicJobPostingBudget200Response.to_json())

# convert the object into a dict
get_classic_job_posting_budget200_response_dict = get_classic_job_posting_budget200_response_instance.to_dict()
# create an instance of GetClassicJobPostingBudget200Response from a dict
get_classic_job_posting_budget200_response_from_dict = GetClassicJobPostingBudget200Response.from_dict(get_classic_job_posting_budget200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


