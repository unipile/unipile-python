# PostsSearchResults


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PostsSearchResultsDataInner]**](PostsSearchResultsDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.posts_search_results import PostsSearchResults

# TODO update the JSON string below
json = "{}"
# create an instance of PostsSearchResults from a JSON string
posts_search_results_instance = PostsSearchResults.from_json(json)
# print the JSON string representation of the object
print(PostsSearchResults.to_json())

# convert the object into a dict
posts_search_results_dict = posts_search_results_instance.to_dict()
# create an instance of PostsSearchResults from a dict
posts_search_results_from_dict = PostsSearchResults.from_dict(posts_search_results_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


