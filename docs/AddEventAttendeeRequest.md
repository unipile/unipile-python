# AddEventAttendeeRequest

The user to invite.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the user to invite to the event. | 

## Example

```python
from unipile.models.add_event_attendee_request import AddEventAttendeeRequest

# TODO update the JSON string below
json = "{}"
# create an instance of AddEventAttendeeRequest from a JSON string
add_event_attendee_request_instance = AddEventAttendeeRequest.from_json(json)
# print the JSON string representation of the object
print(AddEventAttendeeRequest.to_json())

# convert the object into a dict
add_event_attendee_request_dict = add_event_attendee_request_instance.to_dict()
# create an instance of AddEventAttendeeRequest from a dict
add_event_attendee_request_from_dict = AddEventAttendeeRequest.from_dict(add_event_attendee_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


