# JobsSearchResults1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[JobsSearchResults1DataInner]**](JobsSearchResults1DataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.jobs_search_results1 import JobsSearchResults1

# TODO update the JSON string below
json = "{}"
# create an instance of JobsSearchResults1 from a JSON string
jobs_search_results1_instance = JobsSearchResults1.from_json(json)
# print the JSON string representation of the object
print(JobsSearchResults1.to_json())

# convert the object into a dict
jobs_search_results1_dict = jobs_search_results1_instance.to_dict()
# create an instance of JobsSearchResults1 from a dict
jobs_search_results1_from_dict = JobsSearchResults1.from_dict(jobs_search_results1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


