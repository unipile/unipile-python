# GetPostsList200ResponseDataInnerAnalytics

Analytics data of the post.

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
from unipile.models.get_posts_list200_response_data_inner_analytics import GetPostsList200ResponseDataInnerAnalytics

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostsList200ResponseDataInnerAnalytics from a JSON string
get_posts_list200_response_data_inner_analytics_instance = GetPostsList200ResponseDataInnerAnalytics.from_json(json)
# print the JSON string representation of the object
print(GetPostsList200ResponseDataInnerAnalytics.to_json())

# convert the object into a dict
get_posts_list200_response_data_inner_analytics_dict = get_posts_list200_response_data_inner_analytics_instance.to_dict()
# create an instance of GetPostsList200ResponseDataInnerAnalytics from a dict
get_posts_list200_response_data_inner_analytics_from_dict = GetPostsList200ResponseDataInnerAnalytics.from_dict(get_posts_list200_response_data_inner_analytics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


