# GetProfileViews200ResponseAnalytics

Profile views analytics will only be present in the first request of a series of paginated requests.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**views_count** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**highlights** | [**GetProfileViews200ResponseAnalyticsHighlights**](GetProfileViews200ResponseAnalyticsHighlights.md) |  | [optional] 
**details** | [**GetProfileViews200ResponseAnalyticsDetails**](GetProfileViews200ResponseAnalyticsDetails.md) |  | [optional] 

## Example

```python
from unipile.models.get_profile_views200_response_analytics import GetProfileViews200ResponseAnalytics

# TODO update the JSON string below
json = "{}"
# create an instance of GetProfileViews200ResponseAnalytics from a JSON string
get_profile_views200_response_analytics_instance = GetProfileViews200ResponseAnalytics.from_json(json)
# print the JSON string representation of the object
print(GetProfileViews200ResponseAnalytics.to_json())

# convert the object into a dict
get_profile_views200_response_analytics_dict = get_profile_views200_response_analytics_instance.to_dict()
# create an instance of GetProfileViews200ResponseAnalytics from a dict
get_profile_views200_response_analytics_from_dict = GetProfileViews200ResponseAnalytics.from_dict(get_profile_views200_response_analytics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


