# GetCalendarEventList200ResponseDataInnerStart

The start date and time of the event.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Indicates a date-time value. | 
**date_time** | **str** | The date and time. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SSZ). | 
**var_date** | **str** | The date. Uses ISO 8601 date format (YYYY-MM-DD). | 

## Example

```python
from unipile.models.get_calendar_event_list200_response_data_inner_start import GetCalendarEventList200ResponseDataInnerStart

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarEventList200ResponseDataInnerStart from a JSON string
get_calendar_event_list200_response_data_inner_start_instance = GetCalendarEventList200ResponseDataInnerStart.from_json(json)
# print the JSON string representation of the object
print(GetCalendarEventList200ResponseDataInnerStart.to_json())

# convert the object into a dict
get_calendar_event_list200_response_data_inner_start_dict = get_calendar_event_list200_response_data_inner_start_instance.to_dict()
# create an instance of GetCalendarEventList200ResponseDataInnerStart from a dict
get_calendar_event_list200_response_data_inner_start_from_dict = GetCalendarEventList200ResponseDataInnerStart.from_dict(get_calendar_event_list200_response_data_inner_start_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


