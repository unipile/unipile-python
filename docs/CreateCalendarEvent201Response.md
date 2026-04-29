# CreateCalendarEvent201Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the calendar event. | 
**master_event_id** | **str** | If event instance, the ID of the master event. | [optional] 
**calendar_id** | **str** | The ID of the calendar the event belongs to. | 
**created_at** | **str** | The date the event was created. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SSZ). | 
**updated_at** | **str** | The date the event was last updated. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**title** | **str** | The title of the event. | 
**body** | **str** | The body of the event. | [optional] 
**location** | **str** | The location of the event. | [optional] 
**is_cancelled** | **bool** | Is the event cancelled. | 
**is_all_day** | **bool** | Is the event all day. | 
**is_attendees_list_hidden** | **bool** | Is the attendees list hidden for attendees. | 
**attendees** | [**List[GetCalendarEventList200ResponseDataInnerAttendeesInner]**](GetCalendarEventList200ResponseDataInnerAttendeesInner.md) | The attendees of the event. | [optional] 
**start** | [**GetCalendarEventList200ResponseDataInnerStart**](GetCalendarEventList200ResponseDataInnerStart.md) |  | 
**end** | [**GetCalendarEventList200ResponseDataInnerEnd**](GetCalendarEventList200ResponseDataInnerEnd.md) |  | 
**recurrence** | **List[str]** | List of RRULE, EXRULE, RDATE and EXDATE lines for a recurring event, as specified in RFC5545. | [optional] 
**organizer** | [**GetCalendarEventList200ResponseDataInnerOrganizer**](GetCalendarEventList200ResponseDataInnerOrganizer.md) |  | 
**conference** | [**GetCalendarEventList200ResponseDataInnerConference**](GetCalendarEventList200ResponseDataInnerConference.md) |  | [optional] 
**visibility** | **str** | The visibility of the event.         - &#x60;public&#x60; is visible to all.         - &#x60;private&#x60; is visible only to the calendar owner. | 
**transparency** | **str** | The transparency of the event.         - &#x60;opaque&#x60; does block time on the calendar and is equivalent to setting Show me as to Busy in the Calendar UI.         - &#x60;transparent&#x60; does not block time on the calendar and is equivalent to setting Show me as to Available in the Calendar UI. | 
**event_type** | **str** | The type of the event (&#x60;birthday&#x60;, &#x60;fromGmail&#x60;, &#x60;outOfOffice&#x60;...) | [default to 'default']
**background_color** | **str** | Background color of the calendar in hexadecimal format. | [optional] 
**text_color** | **str** | Foreground color of the event in hexadecimal format. | [optional] 

## Example

```python
from unipile.models.create_calendar_event201_response import CreateCalendarEvent201Response

# TODO update the JSON string below
json = "{}"
# create an instance of CreateCalendarEvent201Response from a JSON string
create_calendar_event201_response_instance = CreateCalendarEvent201Response.from_json(json)
# print the JSON string representation of the object
print(CreateCalendarEvent201Response.to_json())

# convert the object into a dict
create_calendar_event201_response_dict = create_calendar_event201_response_instance.to_dict()
# create an instance of CreateCalendarEvent201Response from a dict
create_calendar_event201_response_from_dict = CreateCalendarEvent201Response.from_dict(create_calendar_event201_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


