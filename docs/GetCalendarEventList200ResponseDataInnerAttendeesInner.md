# GetCalendarEventList200ResponseDataInnerAttendeesInner

An attendee of a calendar event.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **str** | Email address of the attendee. | 
**display_name** | **str** | Display name of the attendee. | [optional] 
**comment** | **str** | The response comment of the attendee. | [optional] 
**is_organizer** | **bool** | Is the attendee the organizer of the event. | 
**is_optional** | **bool** | Is the attendee optional (based on type). | 
**is_resource** | **bool** | Is the attendee a resource (based on type). | 
**type** | **str** | Type of the attendee.           - &#x60;required&#x60; is a required attendee.           - &#x60;optional&#x60; is an optional attendee.           - &#x60;resource&#x60; is a resource attendee like a room or a device. | 
**response_status** | **str** | The response status of the attendee.           - &#x60;yes&#x60; if the invitation is accepted.           - &#x60;no&#x60; if the invitation is declined.           - &#x60;maybe&#x60; if the attendee is not sure.           - &#x60;noreply&#x60; if the invitation is pending. | 

## Example

```python
from unipile.models.get_calendar_event_list200_response_data_inner_attendees_inner import GetCalendarEventList200ResponseDataInnerAttendeesInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarEventList200ResponseDataInnerAttendeesInner from a JSON string
get_calendar_event_list200_response_data_inner_attendees_inner_instance = GetCalendarEventList200ResponseDataInnerAttendeesInner.from_json(json)
# print the JSON string representation of the object
print(GetCalendarEventList200ResponseDataInnerAttendeesInner.to_json())

# convert the object into a dict
get_calendar_event_list200_response_data_inner_attendees_inner_dict = get_calendar_event_list200_response_data_inner_attendees_inner_instance.to_dict()
# create an instance of GetCalendarEventList200ResponseDataInnerAttendeesInner from a dict
get_calendar_event_list200_response_data_inner_attendees_inner_from_dict = GetCalendarEventList200ResponseDataInnerAttendeesInner.from_dict(get_calendar_event_list200_response_data_inner_attendees_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


