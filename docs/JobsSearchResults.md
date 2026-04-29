# JobsSearchResults


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[JobsSearchResultsDataInner]**](JobsSearchResultsDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.jobs_search_results import JobsSearchResults

# TODO update the JSON string below
json = "{}"
# create an instance of JobsSearchResults from a JSON string
jobs_search_results_instance = JobsSearchResults.from_json(json)
# print the JSON string representation of the object
print(JobsSearchResults.to_json())

# convert the object into a dict
jobs_search_results_dict = jobs_search_results_instance.to_dict()
# create an instance of JobsSearchResults from a dict
jobs_search_results_from_dict = JobsSearchResults.from_dict(jobs_search_results_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


