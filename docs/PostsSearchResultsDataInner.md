# PostsSearchResultsDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the post for the provider. | 
**share_url** | **str** | The URL to share the post. | 
**created_at** | **str** | The creation date of the post. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**title** | **str** | The title of the post. | [optional] 
**text** | **str** | The text content of the post. | 
**author** | [**GetPostsList200ResponseDataInnerAuthor**](GetPostsList200ResponseDataInnerAuthor.md) |  | 
**user_reacted** | [**GetPostsList200ResponseDataInnerQuotedPostUserReacted**](GetPostsList200ResponseDataInnerQuotedPostUserReacted.md) |  | 
**permissions** | [**GetPostsList200ResponseDataInnerPermissions**](GetPostsList200ResponseDataInnerPermissions.md) |  | 
**reactions_counter** | [**List[GetMessagesList200ResponseDataInnerReactionsCounterInner]**](GetMessagesList200ResponseDataInnerReactionsCounterInner.md) | A list of reactions to the element. | 
**comments_counter** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**reposts_counter** | **float** | The number of reposts of the post. &#x60;null&#x60; if counter is hidden. | 
**poll** | [**GetPostsList200ResponseDataInnerPoll**](GetPostsList200ResponseDataInnerPoll.md) |  | [optional] 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | List of post attachments. | 
**analytics** | [**GetPostsList200ResponseDataInnerAnalytics**](GetPostsList200ResponseDataInnerAnalytics.md) |  | [optional] 
**is_repost** | **bool** | &#x60;true&#x60; if this post is reposted by someone without quote. Quoted post does not qualify as a repost. | 
**reposted_by** | [**GetPostsList200ResponseDataInnerRepostedBy**](GetPostsList200ResponseDataInnerRepostedBy.md) |  | [optional] 
**quoted_post** | [**GetPostsList200ResponseDataInnerQuotedPost**](GetPostsList200ResponseDataInnerQuotedPost.md) |  | [optional] 

## Example

```python
from unipile.models.posts_search_results_data_inner import PostsSearchResultsDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of PostsSearchResultsDataInner from a JSON string
posts_search_results_data_inner_instance = PostsSearchResultsDataInner.from_json(json)
# print the JSON string representation of the object
print(PostsSearchResultsDataInner.to_json())

# convert the object into a dict
posts_search_results_data_inner_dict = posts_search_results_data_inner_instance.to_dict()
# create an instance of PostsSearchResultsDataInner from a dict
posts_search_results_data_inner_from_dict = PostsSearchResultsDataInner.from_dict(posts_search_results_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


