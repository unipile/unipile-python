# PerformEventsSearch200ResponseDataInner

An event of a social network.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;SocialEvent&#x60;. | 
**id** | **str** | The ID of the event for the provider. | 
**name** | **str** | The name of the event. | 
**url** | **str** | The URL of the event page. | 
**description** | **str** | The description of the event. | [optional] 
**start** | [**PerformEventsSearch200ResponseDataInnerStart**](PerformEventsSearch200ResponseDataInnerStart.md) |  | [optional] 
**end** | [**PerformEventsSearch200ResponseDataInnerEnd**](PerformEventsSearch200ResponseDataInnerEnd.md) |  | [optional] 
**timezone** | **str** | The IANA timezone when start and end share the same timezone (e.g. &#x60;Europe/Paris&#x60;). Omitted when they differ; use &#x60;start.timezone&#x60; and &#x60;end.timezone&#x60; instead. | [optional] 
**is_online** | **bool** | Whether the event takes place online. | [optional] 
**online_url** | **str** | The link to join the event online. | [optional] 
**location** | **str** | Where the event takes place, as the provider names it. | [optional] 
**public_picture_url** | **str** | Public url to the picture of the event. | [optional] 
**organizer** | [**PerformEventsSearch200ResponseDataInnerOrganizer**](PerformEventsSearch200ResponseDataInnerOrganizer.md) |  | [optional] 
**group_id** | **str** | The ID of the social group the event belongs to. | [optional] 
**visibility** | **str** | Who can see the event.   - &#x60;public&#x60; anyone.   - &#x60;private&#x60; only the people invited.   - &#x60;friends&#x60; the relations of the organizer.   - &#x60;group&#x60; the members of the group it belongs to. | [optional] 
**is_cancelled** | **bool** | Whether the event was cancelled. | [optional] 
**is_host** | **bool** | Whether the account owner hosts the event. | [optional] 
**attendees_count** | **float** | The number of people going to the event. | [optional] 
**response_status** | **str** | The response to the event.   - &#x60;yes&#x60; going.   - &#x60;maybe&#x60; interested.   - &#x60;no&#x60; not going.   - &#x60;noreply&#x60; invited, without a response yet. | [optional] 

## Example

```python
from unipile.models.perform_events_search200_response_data_inner import PerformEventsSearch200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformEventsSearch200ResponseDataInner from a JSON string
perform_events_search200_response_data_inner_instance = PerformEventsSearch200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(PerformEventsSearch200ResponseDataInner.to_json())

# convert the object into a dict
perform_events_search200_response_data_inner_dict = perform_events_search200_response_data_inner_instance.to_dict()
# create an instance of PerformEventsSearch200ResponseDataInner from a dict
perform_events_search200_response_data_inner_from_dict = PerformEventsSearch200ResponseDataInner.from_dict(perform_events_search200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


