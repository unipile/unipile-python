# PerformClassicJobsSearch200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PerformClassicJobsSearch200ResponseDataInner]**](PerformClassicJobsSearch200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.perform_classic_jobs_search200_response import PerformClassicJobsSearch200Response

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicJobsSearch200Response from a JSON string
perform_classic_jobs_search200_response_instance = PerformClassicJobsSearch200Response.from_json(json)
# print the JSON string representation of the object
print(PerformClassicJobsSearch200Response.to_json())

# convert the object into a dict
perform_classic_jobs_search200_response_dict = perform_classic_jobs_search200_response_instance.to_dict()
# create an instance of PerformClassicJobsSearch200Response from a dict
perform_classic_jobs_search200_response_from_dict = PerformClassicJobsSearch200Response.from_dict(perform_classic_jobs_search200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


