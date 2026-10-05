# GetProfileViews200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**entities** | [**List[GetProfileViews200ResponseEntitiesInner]**](GetProfileViews200ResponseEntitiesInner.md) | A collection of profile view entities. | 
**analytics** | [**GetProfileViews200ResponseAnalytics**](GetProfileViews200ResponseAnalytics.md) |  | [optional] 

## Example

```python
from unipile.models.get_profile_views200_response import GetProfileViews200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetProfileViews200Response from a JSON string
get_profile_views200_response_instance = GetProfileViews200Response.from_json(json)
# print the JSON string representation of the object
print(GetProfileViews200Response.to_json())

# convert the object into a dict
get_profile_views200_response_dict = get_profile_views200_response_instance.to_dict()
# create an instance of GetProfileViews200Response from a dict
get_profile_views200_response_from_dict = GetProfileViews200Response.from_dict(get_profile_views200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


