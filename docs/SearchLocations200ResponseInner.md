# SearchLocations200ResponseInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the Instagram location. | 
**source** | **str** | The source provider of the location. | 
**name** | **str** | The name of the location. | 
**address** | **str** | The street address of the location. | [optional] 
**latitude** | **float** | The latitude coordinate of the location. | [optional] 
**longitude** | **float** | The longitude coordinate of the location. | [optional] 

## Example

```python
from unipile.models.search_locations200_response_inner import SearchLocations200ResponseInner

# TODO update the JSON string below
json = "{}"
# create an instance of SearchLocations200ResponseInner from a JSON string
search_locations200_response_inner_instance = SearchLocations200ResponseInner.from_json(json)
# print the JSON string representation of the object
print(SearchLocations200ResponseInner.to_json())

# convert the object into a dict
search_locations200_response_inner_dict = search_locations200_response_inner_instance.to_dict()
# create an instance of SearchLocations200ResponseInner from a dict
search_locations200_response_inner_from_dict = SearchLocations200ResponseInner.from_dict(search_locations200_response_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


