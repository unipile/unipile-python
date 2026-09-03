# CancelCalendarEventRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**comment** | **str** | A message about the cancellation sent to the attendees. Only available for outlook. | [optional] 

## Example

```python
from unipile.models.cancel_calendar_event_request import CancelCalendarEventRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CancelCalendarEventRequest from a JSON string
cancel_calendar_event_request_instance = CancelCalendarEventRequest.from_json(json)
# print the JSON string representation of the object
print(CancelCalendarEventRequest.to_json())

# convert the object into a dict
cancel_calendar_event_request_dict = cancel_calendar_event_request_instance.to_dict()
# create an instance of CancelCalendarEventRequest from a dict
cancel_calendar_event_request_from_dict = CancelCalendarEventRequest.from_dict(cancel_calendar_event_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


