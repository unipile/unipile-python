# CreateEventRequest

The event to create.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The name of the event. | 
**start_at** | **datetime** | The start of the event, in the future. Must use a supported date-time format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). | 
**end_at** | **datetime** | The end of the event, after its start. Must use a supported date-time format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). | [optional] 
**timezone** | **str** | The IANA time zone the event is shown in (e.g. Europe/Paris). Defaults to UTC. | [optional] 
**description** | **str** | The description of the event. | [optional] 
**is_online** | **bool** | Whether the event takes place online. | [optional] [default to False]
**online_url** | **str** | The link to join the event online (for an online event). | [optional] 
**location** | **str** | Where the event takes place (for an in-person event): a venue or an address. | [optional] 
**visibility** | **str** | Who can see the event.   - &#x60;public&#x60; anyone.   - &#x60;private&#x60; only the people invited.   - &#x60;friends&#x60; the relations of the organizer.   - &#x60;group&#x60; the members of the group it belongs to. | [optional] 
**group_id** | **str** | The ID of the social group where the event will be created (if supported by the provider). | [optional] 
**invite_group_members** | **bool** | For an event in a group, whether to invite all the members of the group (if supported by the provider). | [optional] 
**co_host_ids** | **List[str]** | The IDs of the users co-hosting the event (if supported by the provider). | [optional] 
**can_attendees_invite** | **bool** | Whether the attendees of a private event can invite other people (if supported by the provider). | [optional] 
**is_attendees_list_hidden** | **bool** | Whether to hide the list of attendees from the attendees (if supported by the provider). | [optional] 

## Example

```python
from unipile.models.create_event_request import CreateEventRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateEventRequest from a JSON string
create_event_request_instance = CreateEventRequest.from_json(json)
# print the JSON string representation of the object
print(CreateEventRequest.to_json())

# convert the object into a dict
create_event_request_dict = create_event_request_instance.to_dict()
# create an instance of CreateEventRequest from a dict
create_event_request_from_dict = CreateEventRequest.from_dict(create_event_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


