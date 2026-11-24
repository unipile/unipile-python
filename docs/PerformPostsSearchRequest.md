# PerformPostsSearchRequest

The criteria of the search.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | The keywords to search posts for. | 
**sort_by** | **str** | The order of the posts.   - &#x60;most_relevant&#x60; the most relevant first.   - &#x60;most_recent&#x60; the most recent first. | [optional] [default to 'most_relevant']
**seen** | **bool** | Only return the posts the account owner has already seen. | [optional] 
**start_date** | **date** | Only return the posts published on or after this day. Must use a supported date format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). | [optional] 
**end_date** | **date** | Only return the posts published on or before this day. Must use a supported date format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). | [optional] 
**posted_by** | [**PerformPostsSearchRequestPostedBy**](PerformPostsSearchRequestPostedBy.md) |  | [optional] 
**location** | **List[str]** | Only return the posts tagged in one of these cities. Use the IDs of &#x60;location&#x60; search parameters. | [optional] 

## Example

```python
from unipile.models.perform_posts_search_request import PerformPostsSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformPostsSearchRequest from a JSON string
perform_posts_search_request_instance = PerformPostsSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformPostsSearchRequest.to_json())

# convert the object into a dict
perform_posts_search_request_dict = perform_posts_search_request_instance.to_dict()
# create an instance of PerformPostsSearchRequest from a dict
perform_posts_search_request_from_dict = PerformPostsSearchRequest.from_dict(perform_posts_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


