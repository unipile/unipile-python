# PerformClassicPostsSearchRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | A keyword or group of keywords. | [optional] 
**sort_by** | **str** | The sort method.    Native filter : Sort by    | [optional] 
**date_posted** | **str** | The time period when the posts should have been published.    Native filter : Date posted    | [optional] 
**content_type** | **str** | Any media or non text-only resource that should be included in the posts.    Native filter : Content type    | [optional] 
**posted_by** | [**PerformClassicPostsSearchRequestPostedBy**](PerformClassicPostsSearchRequestPostedBy.md) |  | [optional] 
**mentioning** | [**PerformClassicPostsSearchRequestMentioning**](PerformClassicPostsSearchRequestMentioning.md) |  | [optional] 
**author** | [**PerformClassicPostsSearchRequestAuthor**](PerformClassicPostsSearchRequestAuthor.md) |  | [optional] 

## Example

```python
from unipile.models.perform_classic_posts_search_request import PerformClassicPostsSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicPostsSearchRequest from a JSON string
perform_classic_posts_search_request_instance = PerformClassicPostsSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformClassicPostsSearchRequest.to_json())

# convert the object into a dict
perform_classic_posts_search_request_dict = perform_classic_posts_search_request_instance.to_dict()
# create an instance of PerformClassicPostsSearchRequest from a dict
perform_classic_posts_search_request_from_dict = PerformClassicPostsSearchRequest.from_dict(perform_classic_posts_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


