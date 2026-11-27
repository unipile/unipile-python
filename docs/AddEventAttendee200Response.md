# AddEventAttendee200Response

The user was invited to the event.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;EventAttendeeInvited&#x60;. | 

## Example

```python
from unipile.models.add_event_attendee200_response import AddEventAttendee200Response

# TODO update the JSON string below
json = "{}"
# create an instance of AddEventAttendee200Response from a JSON string
add_event_attendee200_response_instance = AddEventAttendee200Response.from_json(json)
# print the JSON string representation of the object
print(AddEventAttendee200Response.to_json())

# convert the object into a dict
add_event_attendee200_response_dict = add_event_attendee200_response_instance.to_dict()
# create an instance of AddEventAttendee200Response from a dict
add_event_attendee200_response_from_dict = AddEventAttendee200Response.from_dict(add_event_attendee200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


