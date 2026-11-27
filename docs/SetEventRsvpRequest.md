# SetEventRsvpRequest

The response of the account owner to the event.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | The response of the account owner to the event.   - &#x60;yes&#x60; going.   - &#x60;maybe&#x60; interested.   - &#x60;no&#x60; not going. | 

## Example

```python
from unipile.models.set_event_rsvp_request import SetEventRsvpRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SetEventRsvpRequest from a JSON string
set_event_rsvp_request_instance = SetEventRsvpRequest.from_json(json)
# print the JSON string representation of the object
print(SetEventRsvpRequest.to_json())

# convert the object into a dict
set_event_rsvp_request_dict = set_event_rsvp_request_instance.to_dict()
# create an instance of SetEventRsvpRequest from a dict
set_event_rsvp_request_from_dict = SetEventRsvpRequest.from_dict(set_event_rsvp_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


