# JobsSearchResultsDataInnerCompany

The company that published the Job posting.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the Company. | [optional] 
**name** | **str** | The name of the Company. | 
**public_identifier** | **str** | The public identifier of the Company. | [optional] 
**profile_url** | **str** | The profile URL of the Company. | [optional] 
**public_picture_url** | **str** | The profile picture URL of the Company. | [optional] 

## Example

```python
from unipile.models.jobs_search_results_data_inner_company import JobsSearchResultsDataInnerCompany

# TODO update the JSON string below
json = "{}"
# create an instance of JobsSearchResultsDataInnerCompany from a JSON string
jobs_search_results_data_inner_company_instance = JobsSearchResultsDataInnerCompany.from_json(json)
# print the JSON string representation of the object
print(JobsSearchResultsDataInnerCompany.to_json())

# convert the object into a dict
jobs_search_results_data_inner_company_dict = jobs_search_results_data_inner_company_instance.to_dict()
# create an instance of JobsSearchResultsDataInnerCompany from a dict
jobs_search_results_data_inner_company_from_dict = JobsSearchResultsDataInnerCompany.from_dict(jobs_search_results_data_inner_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


