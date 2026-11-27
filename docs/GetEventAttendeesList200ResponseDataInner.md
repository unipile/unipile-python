# GetEventAttendeesList200ResponseDataInner

A guest of an event and their response to it.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;SocialEventAttendee&#x60;. | 
**user** | [**GetEventAttendeesList200ResponseDataInnerUser**](GetEventAttendeesList200ResponseDataInnerUser.md) |  | 
**response_status** | **str** | The response to the event.   - &#x60;yes&#x60; going.   - &#x60;maybe&#x60; interested.   - &#x60;no&#x60; not going.   - &#x60;noreply&#x60; invited, without a response yet. | 
**is_self** | **bool** | Whether the attendee is the account owner. | 

## Example

```python
from unipile.models.get_event_attendees_list200_response_data_inner import GetEventAttendeesList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetEventAttendeesList200ResponseDataInner from a JSON string
get_event_attendees_list200_response_data_inner_instance = GetEventAttendeesList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetEventAttendeesList200ResponseDataInner.to_json())

# convert the object into a dict
get_event_attendees_list200_response_data_inner_dict = get_event_attendees_list200_response_data_inner_instance.to_dict()
# create an instance of GetEventAttendeesList200ResponseDataInner from a dict
get_event_attendees_list200_response_data_inner_from_dict = GetEventAttendeesList200ResponseDataInner.from_dict(get_event_attendees_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


