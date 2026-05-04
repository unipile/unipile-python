# GetPostsList200ResponseDataInnerEvent

Data about the event if the post is an event.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the event. | 
**name** | **str** | The name of the event. | 
**url** | **str** | The link to the event. | [optional] 
**online** | **bool** | Whether the event is an online event. | 
**location** | **str** | The location of the event. | [optional] 
**description** | **str** | The description of the event. | [optional] 
**public_picture_url** | **str** | Public url to the picture of the event. | [optional] 
**starts_on** | **str** | The date when the event will start. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**ends_on** | **str** | The date when the event will end. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 

## Example

```python
from unipile.models.get_posts_list200_response_data_inner_event import GetPostsList200ResponseDataInnerEvent

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostsList200ResponseDataInnerEvent from a JSON string
get_posts_list200_response_data_inner_event_instance = GetPostsList200ResponseDataInnerEvent.from_json(json)
# print the JSON string representation of the object
print(GetPostsList200ResponseDataInnerEvent.to_json())

# convert the object into a dict
get_posts_list200_response_data_inner_event_dict = get_posts_list200_response_data_inner_event_instance.to_dict()
# create an instance of GetPostsList200ResponseDataInnerEvent from a dict
get_posts_list200_response_data_inner_event_from_dict = GetPostsList200ResponseDataInnerEvent.from_dict(get_posts_list200_response_data_inner_event_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


