# GetProfileViews200ResponseAnalyticsDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**locations** | **Dict[str, Optional[str]]** |  | [optional] 
**companies** | **Dict[str, str]** |  | [optional] 
**industries** | **Dict[str, str]** |  | [optional] 

## Example

```python
from unipile.models.get_profile_views200_response_analytics_details import GetProfileViews200ResponseAnalyticsDetails

# TODO update the JSON string below
json = "{}"
# create an instance of GetProfileViews200ResponseAnalyticsDetails from a JSON string
get_profile_views200_response_analytics_details_instance = GetProfileViews200ResponseAnalyticsDetails.from_json(json)
# print the JSON string representation of the object
print(GetProfileViews200ResponseAnalyticsDetails.to_json())

# convert the object into a dict
get_profile_views200_response_analytics_details_dict = get_profile_views200_response_analytics_details_instance.to_dict()
# create an instance of GetProfileViews200ResponseAnalyticsDetails from a dict
get_profile_views200_response_analytics_details_from_dict = GetProfileViews200ResponseAnalyticsDetails.from_dict(get_profile_views200_response_analytics_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


