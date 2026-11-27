# PerformEventsSearch200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PerformEventsSearch200ResponseDataInner]**](PerformEventsSearch200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the provider. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.perform_events_search200_response import PerformEventsSearch200Response

# TODO update the JSON string below
json = "{}"
# create an instance of PerformEventsSearch200Response from a JSON string
perform_events_search200_response_instance = PerformEventsSearch200Response.from_json(json)
# print the JSON string representation of the object
print(PerformEventsSearch200Response.to_json())

# convert the object into a dict
perform_events_search200_response_dict = perform_events_search200_response_instance.to_dict()
# create an instance of PerformEventsSearch200Response from a dict
perform_events_search200_response_from_dict = PerformEventsSearch200Response.from_dict(perform_events_search200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


