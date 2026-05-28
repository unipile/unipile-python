# JobsSearchResults1DataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the Job posting. | 
**title** | **str** | The title of the Job posting. | 
**location** | **str** | The location of the Job posting. | [optional] 
**listed_at** | **str** | The creation date of the Job posting. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**workplace_type** | **str** | The type of workplace of the Job posting. | [optional] 
**url** | **str** | The URL of the Job posting. | 
**is_repost** | **bool** | Whether the Job posting is a repost. | 
**is_promoted** | **bool** | Whether the Job posting has been promoted. | 
**easy_apply** | **bool** | Whether applicants are allowed to apply to the Job posting directly on LinkedIn. | 
**few_applicants** | **bool** | Whether the Job posting received a limited number of applications. | 
**company** | [**JobsSearchResultsDataInnerCompany**](JobsSearchResultsDataInnerCompany.md) |  | 
**insights** | **List[str]** | A list of insights about the Job posting. | 

## Example

```python
from unipile.models.jobs_search_results1_data_inner import JobsSearchResults1DataInner

# TODO update the JSON string below
json = "{}"
# create an instance of JobsSearchResults1DataInner from a JSON string
jobs_search_results1_data_inner_instance = JobsSearchResults1DataInner.from_json(json)
# print the JSON string representation of the object
print(JobsSearchResults1DataInner.to_json())

# convert the object into a dict
jobs_search_results1_data_inner_dict = jobs_search_results1_data_inner_instance.to_dict()
# create an instance of JobsSearchResults1DataInner from a dict
jobs_search_results1_data_inner_from_dict = JobsSearchResults1DataInner.from_dict(jobs_search_results1_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


