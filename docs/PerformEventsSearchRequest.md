# PerformEventsSearchRequest

The criteria of the search.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | The keywords to search events for. | 
**start_date** | **date** | Only return the events taking place on or after this day, if supported by the provider. Must use a supported date format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). | [optional] 
**end_date** | **date** | Only return the events taking place on or before this day, if supported by the provider. Must use a supported date format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). | [optional] 
**location** | **List[str]** | Only return the events taking place around one of these cities, if supported by the provider. Use the IDs of &#x60;location&#x60; search parameters. | [optional] 
**category** | **List[str]** | Only return the events of one of these categories, if supported by the provider. Use the IDs of &#x60;event_category&#x60; search parameters. | [optional] 

## Example

```python
from unipile.models.perform_events_search_request import PerformEventsSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformEventsSearchRequest from a JSON string
perform_events_search_request_instance = PerformEventsSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformEventsSearchRequest.to_json())

# convert the object into a dict
perform_events_search_request_dict = perform_events_search_request_instance.to_dict()
# create an instance of PerformEventsSearchRequest from a dict
perform_events_search_request_from_dict = PerformEventsSearchRequest.from_dict(perform_events_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


