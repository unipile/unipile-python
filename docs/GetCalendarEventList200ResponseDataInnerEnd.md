# GetCalendarEventList200ResponseDataInnerEnd

The end date and time of the event.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Indicates a date-time value. | 
**date_time** | **str** | The date and time. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SSZ). | 
**var_date** | **str** | The date. Uses ISO 8601 date format (YYYY-MM-DD). | 

## Example

```python
from unipile.models.get_calendar_event_list200_response_data_inner_end import GetCalendarEventList200ResponseDataInnerEnd

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarEventList200ResponseDataInnerEnd from a JSON string
get_calendar_event_list200_response_data_inner_end_instance = GetCalendarEventList200ResponseDataInnerEnd.from_json(json)
# print the JSON string representation of the object
print(GetCalendarEventList200ResponseDataInnerEnd.to_json())

# convert the object into a dict
get_calendar_event_list200_response_data_inner_end_dict = get_calendar_event_list200_response_data_inner_end_instance.to_dict()
# create an instance of GetCalendarEventList200ResponseDataInnerEnd from a dict
get_calendar_event_list200_response_data_inner_end_from_dict = GetCalendarEventList200ResponseDataInnerEnd.from_dict(get_calendar_event_list200_response_data_inner_end_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


