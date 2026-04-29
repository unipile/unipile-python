# PerformClassicPostsSearchRequestMentioning

The users/companies mentionned in the posts.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**member** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;PEOPLE&#x60; type to find out the possible values.    Native filter : Mentioning member    | [optional] 
**company** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;COMPANY&#x60; type to find out the possible values.    Native filter : Mentioning company    | [optional] 

## Example

```python
from unipile.models.perform_classic_posts_search_request_mentioning import PerformClassicPostsSearchRequestMentioning

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicPostsSearchRequestMentioning from a JSON string
perform_classic_posts_search_request_mentioning_instance = PerformClassicPostsSearchRequestMentioning.from_json(json)
# print the JSON string representation of the object
print(PerformClassicPostsSearchRequestMentioning.to_json())

# convert the object into a dict
perform_classic_posts_search_request_mentioning_dict = perform_classic_posts_search_request_mentioning_instance.to_dict()
# create an instance of PerformClassicPostsSearchRequestMentioning from a dict
perform_classic_posts_search_request_mentioning_from_dict = PerformClassicPostsSearchRequestMentioning.from_dict(perform_classic_posts_search_request_mentioning_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


