# PostAnalytics

Analytics data of the post. Metrics not provided by the provider are omitted.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**impressions_counter** | **float** | The number of impressions of the post. | [optional] 
**engagements_counter** | **float** | The number of engagements of the post. | [optional] 
**engagement_rate** | **float** | The engagement rate of the post. | [optional] 
**clicks_counter** | **float** | The number of clicks of the post. | [optional] 
**clickthrough_rate** | **float** | The clickthrough rate of the post. | [optional] 
**page_viewers_from_this_post_counter** | **float** | The number of page viewers from this post. | [optional] 
**followers_gained_from_this_post_counter** | **float** | The number of followers gained from this post. | [optional] 
**users_reached_counter** | **float** | The number of users reached from this post. | [optional] 

## Example

```python
from unipile.models.post_analytics import PostAnalytics

# TODO update the JSON string below
json = "{}"
# create an instance of PostAnalytics from a JSON string
post_analytics_instance = PostAnalytics.from_json(json)
# print the JSON string representation of the object
print(PostAnalytics.to_json())

# convert the object into a dict
post_analytics_dict = post_analytics_instance.to_dict()
# create an instance of PostAnalytics from a dict
post_analytics_from_dict = PostAnalytics.from_dict(post_analytics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


