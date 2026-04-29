# CompaniesSearchResultsDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the Company. | 
**display_name** | **str** | The display name of the Company. | 
**public_identifier** | **str** | The public identifier of the Company. | [optional] 
**profile_url** | **str** | The profile URL of the Company. | [optional] 
**public_picture_url** | **str** | The public picture URL of the Company. | [optional] 
**public_picture_url_large** | **str** | The public picture URL of the Company in large size. | [optional] 
**location** | **str** | The location of the Company. | [optional] 
**industry** | **str** | The industry to which the Company belongs. | [optional] 
**summary** | **str** | The summary of the Company&#39;s activities. | [optional] 
**relations_count** | **float** | The number of the relations of the Company. | [optional] 
**product** | **str** |  | 
**job_postings_count** | **float** | The number of job postings published by the Company. | [optional] 
**followers_count** | **float** | The number of the followers of the Company. | [optional] 

## Example

```python
from unipile.models.companies_search_results_data_inner import CompaniesSearchResultsDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of CompaniesSearchResultsDataInner from a JSON string
companies_search_results_data_inner_instance = CompaniesSearchResultsDataInner.from_json(json)
# print the JSON string representation of the object
print(CompaniesSearchResultsDataInner.to_json())

# convert the object into a dict
companies_search_results_data_inner_dict = companies_search_results_data_inner_instance.to_dict()
# create an instance of CompaniesSearchResultsDataInner from a dict
companies_search_results_data_inner_from_dict = CompaniesSearchResultsDataInner.from_dict(companies_search_results_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


