# PerformClassicPostsSearchRequestPostedBy

The users/companies who published the posts.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**member** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;PEOPLE&#x60; type to find out the possible values.    Native filter : From member    | [optional] 
**company** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;COMPANY&#x60; type to find out the possible values.    Native filter : From company    | [optional] 
**me** | **bool** | Whether the posts should have been published by yourself.    Native filter : Posted by [Me]    | [optional] 
**relations** | **bool** | Whether the posts should have been published by your relations.    Native filter : Posted by [1st connections]    | [optional] 
**people_you_follow** | **bool** | Whether the posts should have been published by users you follow.    Native filter : Posted by [People you follow]    | [optional] 

## Example

```python
from unipile.models.perform_classic_posts_search_request_posted_by import PerformClassicPostsSearchRequestPostedBy

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicPostsSearchRequestPostedBy from a JSON string
perform_classic_posts_search_request_posted_by_instance = PerformClassicPostsSearchRequestPostedBy.from_json(json)
# print the JSON string representation of the object
print(PerformClassicPostsSearchRequestPostedBy.to_json())

# convert the object into a dict
perform_classic_posts_search_request_posted_by_dict = perform_classic_posts_search_request_posted_by_instance.to_dict()
# create an instance of PerformClassicPostsSearchRequestPostedBy from a dict
perform_classic_posts_search_request_posted_by_from_dict = PerformClassicPostsSearchRequestPostedBy.from_dict(perform_classic_posts_search_request_posted_by_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


