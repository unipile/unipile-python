# PipelineCandidatesSearch


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PipelineCandidatesSearchDataInner]**](PipelineCandidatesSearchDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.pipeline_candidates_search import PipelineCandidatesSearch

# TODO update the JSON string below
json = "{}"
# create an instance of PipelineCandidatesSearch from a JSON string
pipeline_candidates_search_instance = PipelineCandidatesSearch.from_json(json)
# print the JSON string representation of the object
print(PipelineCandidatesSearch.to_json())

# convert the object into a dict
pipeline_candidates_search_dict = pipeline_candidates_search_instance.to_dict()
# create an instance of PipelineCandidatesSearch from a dict
pipeline_candidates_search_from_dict = PipelineCandidatesSearch.from_dict(pipeline_candidates_search_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


