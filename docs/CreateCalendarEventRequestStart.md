# CreateCalendarEventRequestStart

The start date and time of the event. Use date for all day events.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Indicates a date-time value. | 
**date_time** | **str** | The date and time. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SSZ). | 
**var_date** | **str** | The date. Uses ISO 8601 date format (YYYY-MM-DD). | 

## Example

```python
from unipile.models.create_calendar_event_request_start import CreateCalendarEventRequestStart

# TODO update the JSON string below
json = "{}"
# create an instance of CreateCalendarEventRequestStart from a JSON string
create_calendar_event_request_start_instance = CreateCalendarEventRequestStart.from_json(json)
# print the JSON string representation of the object
print(CreateCalendarEventRequestStart.to_json())

# convert the object into a dict
create_calendar_event_request_start_dict = create_calendar_event_request_start_instance.to_dict()
# create an instance of CreateCalendarEventRequestStart from a dict
create_calendar_event_request_start_from_dict = CreateCalendarEventRequestStart.from_dict(create_calendar_event_request_start_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


