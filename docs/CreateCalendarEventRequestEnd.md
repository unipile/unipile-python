# CreateCalendarEventRequestEnd

The end date and time of the event. Use date for all day events.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Indicates a date-time value. | 
**date_time** | **str** | The date and time. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SSZ). | 
**var_date** | **str** | The date. Uses ISO 8601 date format (YYYY-MM-DD). | 

## Example

```python
from unipile.models.create_calendar_event_request_end import CreateCalendarEventRequestEnd

# TODO update the JSON string below
json = "{}"
# create an instance of CreateCalendarEventRequestEnd from a JSON string
create_calendar_event_request_end_instance = CreateCalendarEventRequestEnd.from_json(json)
# print the JSON string representation of the object
print(CreateCalendarEventRequestEnd.to_json())

# convert the object into a dict
create_calendar_event_request_end_dict = create_calendar_event_request_end_instance.to_dict()
# create an instance of CreateCalendarEventRequestEnd from a dict
create_calendar_event_request_end_from_dict = CreateCalendarEventRequestEnd.from_dict(create_calendar_event_request_end_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


