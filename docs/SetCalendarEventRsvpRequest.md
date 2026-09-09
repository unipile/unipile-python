# SetCalendarEventRsvpRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | The response of the connected account to the invitation.           - &#x60;yes&#x60; accepts the invitation.           - &#x60;maybe&#x60; accepts the invitation tentatively.           - &#x60;no&#x60; declines the invitation. | 
**comment** | **str** | A comment sent to the organizer along with the response. | [optional] 

## Example

```python
from unipile.models.set_calendar_event_rsvp_request import SetCalendarEventRsvpRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SetCalendarEventRsvpRequest from a JSON string
set_calendar_event_rsvp_request_instance = SetCalendarEventRsvpRequest.from_json(json)
# print the JSON string representation of the object
print(SetCalendarEventRsvpRequest.to_json())

# convert the object into a dict
set_calendar_event_rsvp_request_dict = set_calendar_event_rsvp_request_instance.to_dict()
# create an instance of SetCalendarEventRsvpRequest from a dict
set_calendar_event_rsvp_request_from_dict = SetCalendarEventRsvpRequest.from_dict(set_calendar_event_rsvp_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


