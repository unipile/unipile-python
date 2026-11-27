# PerformEventsSearch200ResponseDataInnerStart

The start date and time of the event.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Indicates a date-time value. | 
**date_time** | **str** | The date and time. May include a UTC offset, or be expressed as a local date and time without an offset (e.g. &#x60;2026-10-08T10:00:00&#x60;). When no offset is provided, the value is interpreted in &#x60;timezone&#x60;, or in the event-level timezone when set; otherwise it defaults to UTC. | 
**timezone** | **str** | The IANA timezone in which the date is expressed (e.g. &#x60;Europe/Paris&#x60;). | [optional] 
**var_date** | **date** | The date. Must use a supported date format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). | 

## Example

```python
from unipile.models.perform_events_search200_response_data_inner_start import PerformEventsSearch200ResponseDataInnerStart

# TODO update the JSON string below
json = "{}"
# create an instance of PerformEventsSearch200ResponseDataInnerStart from a JSON string
perform_events_search200_response_data_inner_start_instance = PerformEventsSearch200ResponseDataInnerStart.from_json(json)
# print the JSON string representation of the object
print(PerformEventsSearch200ResponseDataInnerStart.to_json())

# convert the object into a dict
perform_events_search200_response_data_inner_start_dict = perform_events_search200_response_data_inner_start_instance.to_dict()
# create an instance of PerformEventsSearch200ResponseDataInnerStart from a dict
perform_events_search200_response_data_inner_start_from_dict = PerformEventsSearch200ResponseDataInnerStart.from_dict(perform_events_search200_response_data_inner_start_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


