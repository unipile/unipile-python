# PerformRecruiterSearchFromUrl200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PipelineCandidatesSearchDataInner]**](PipelineCandidatesSearchDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.perform_recruiter_search_from_url200_response import PerformRecruiterSearchFromUrl200Response

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterSearchFromUrl200Response from a JSON string
perform_recruiter_search_from_url200_response_instance = PerformRecruiterSearchFromUrl200Response.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterSearchFromUrl200Response.to_json())

# convert the object into a dict
perform_recruiter_search_from_url200_response_dict = perform_recruiter_search_from_url200_response_instance.to_dict()
# create an instance of PerformRecruiterSearchFromUrl200Response from a dict
perform_recruiter_search_from_url200_response_from_dict = PerformRecruiterSearchFromUrl200Response.from_dict(perform_recruiter_search_from_url200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


