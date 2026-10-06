# GetProfileViews200ResponseEntitiesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** |  | 
**public_identifier** | **str** | The text content of the message, when available. | 
**name** | **str** | The text content of the message, when available. | 
**picture_url** | **str** | The text content of the message, when available. | [optional] 
**network_distance** | **str** |  | [optional] 
**premium** | **bool** |  | [optional] 
**verified** | **bool** |  | [optional] 
**last_visited** | [**GetProfileViews200ResponseEntitiesInnerLastVisited**](GetProfileViews200ResponseEntitiesInnerLastVisited.md) |  | 

## Example

```python
from unipile.models.get_profile_views200_response_entities_inner import GetProfileViews200ResponseEntitiesInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetProfileViews200ResponseEntitiesInner from a JSON string
get_profile_views200_response_entities_inner_instance = GetProfileViews200ResponseEntitiesInner.from_json(json)
# print the JSON string representation of the object
print(GetProfileViews200ResponseEntitiesInner.to_json())

# convert the object into a dict
get_profile_views200_response_entities_inner_dict = get_profile_views200_response_entities_inner_instance.to_dict()
# create an instance of GetProfileViews200ResponseEntitiesInner from a dict
get_profile_views200_response_entities_inner_from_dict = GetProfileViews200ResponseEntitiesInner.from_dict(get_profile_views200_response_entities_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


