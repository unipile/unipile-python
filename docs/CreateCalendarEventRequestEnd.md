# CreateCalendarEventRequestEnd

The end date and time of the event. Use date for all day events.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Indicates a date-time value. | 
**date_time** | **str** | The date and time. May include a UTC offset, or be expressed as a local date and time without an offset (e.g. &#x60;2026-10-08T10:00:00&#x60;). When no offset is provided, the value is interpreted in &#x60;timezone&#x60;, or in the event-level timezone when set; otherwise it defaults to UTC. | 
**timezone** | **str** | The IANA timezone in which the date is expressed (e.g. &#x60;Europe/Paris&#x60;). | [optional] 
**var_date** | **date** | The date. Must use a supported date format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). | 

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


