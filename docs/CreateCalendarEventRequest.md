# CreateCalendarEventRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **str** | The title of the event. | 
**body** | **str** | The body of the event. | [optional] 
**location** | **str** | The location of the event. | [optional] 
**background_color** | **str** | Background color of the calendar in hexadecimal format. For Google we match the closest palette available | [optional] 
**transparency** | **str** | The transparency of the event.             - &#x60;opaque&#x60; does block time on the calendar and is equivalent to setting Show me as to Busy in the Calendar UI.             - &#x60;transparent&#x60; does not block time on the calendar and is equivalent to setting Show me as to Available in the Calendar UI. | [optional] [default to 'opaque']
**visibility** | **str** | The visibility of the event.             - &#x60;public&#x60; is visible to all.             - &#x60;private&#x60; is visible only to the calendar owner. | [optional] [default to 'public']
**conference** | [**GetCalendarEventList200ResponseDataInnerConference**](GetCalendarEventList200ResponseDataInnerConference.md) |  | [optional] 
**is_attendees_list_hidden** | **bool** | Is the attendees list hidden for attendees. | [optional] 
**attendees** | [**List[CreateCalendarEventRequestAttendeesInner]**](CreateCalendarEventRequestAttendeesInner.md) |  | 
**recurrence** | **List[str]** | List of RRULE, EXRULE, RDATE and EXDATE lines for a recurring event, as specified in RFC5545. | [optional] 
**start** | [**CreateCalendarEventRequestStart**](CreateCalendarEventRequestStart.md) |  | 
**end** | [**CreateCalendarEventRequestEnd**](CreateCalendarEventRequestEnd.md) |  | 

## Example

```python
from unipile.models.create_calendar_event_request import CreateCalendarEventRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateCalendarEventRequest from a JSON string
create_calendar_event_request_instance = CreateCalendarEventRequest.from_json(json)
# print the JSON string representation of the object
print(CreateCalendarEventRequest.to_json())

# convert the object into a dict
create_calendar_event_request_dict = create_calendar_event_request_instance.to_dict()
# create an instance of CreateCalendarEventRequest from a dict
create_calendar_event_request_from_dict = CreateCalendarEventRequest.from_dict(create_calendar_event_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


