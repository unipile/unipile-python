# PerformClassicPostsSearchRequestAuthor


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** |     Native filter : Author keywords    | [optional] 
**company** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;COMPANY&#x60; type to find out the possible values.    Native filter : Author company    | [optional] 
**industry** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;INDUSTRY&#x60; type to find out the possible values.    Native filter : Author industry    | [optional] 

## Example

```python
from unipile.models.perform_classic_posts_search_request_author import PerformClassicPostsSearchRequestAuthor

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicPostsSearchRequestAuthor from a JSON string
perform_classic_posts_search_request_author_instance = PerformClassicPostsSearchRequestAuthor.from_json(json)
# print the JSON string representation of the object
print(PerformClassicPostsSearchRequestAuthor.to_json())

# convert the object into a dict
perform_classic_posts_search_request_author_dict = perform_classic_posts_search_request_author_instance.to_dict()
# create an instance of PerformClassicPostsSearchRequestAuthor from a dict
perform_classic_posts_search_request_author_from_dict = PerformClassicPostsSearchRequestAuthor.from_dict(perform_classic_posts_search_request_author_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


