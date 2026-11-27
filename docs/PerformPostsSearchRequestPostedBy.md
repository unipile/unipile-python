# PerformPostsSearchRequestPostedBy

Only return the posts of these authors, if supported by the provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**me** | **bool** | The posts of the account owner. | [optional] 
**member** | **List[str]** | The posts of these users, given by their IDs. | [optional] 
**company** | **List[str]** | The posts of these pages (companies, brands, public figures...), given by their IDs. | [optional] 
**group** | **List[str]** | The posts published in these groups, given by their IDs. | [optional] 
**my_groups_and_pages** | **bool** | The posts of the groups and pages of the account owner. | [optional] 
**public** | **bool** | Public posts. | [optional] 

## Example

```python
from unipile.models.perform_posts_search_request_posted_by import PerformPostsSearchRequestPostedBy

# TODO update the JSON string below
json = "{}"
# create an instance of PerformPostsSearchRequestPostedBy from a JSON string
perform_posts_search_request_posted_by_instance = PerformPostsSearchRequestPostedBy.from_json(json)
# print the JSON string representation of the object
print(PerformPostsSearchRequestPostedBy.to_json())

# convert the object into a dict
perform_posts_search_request_posted_by_dict = perform_posts_search_request_posted_by_instance.to_dict()
# create an instance of PerformPostsSearchRequestPostedBy from a dict
perform_posts_search_request_posted_by_from_dict = PerformPostsSearchRequestPostedBy.from_dict(perform_posts_search_request_posted_by_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


