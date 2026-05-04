# GetUserCommentsList200ResponseDataInnerParentPost


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the post for the provider. | 
**share_url** | **str** | The URL to share the post. | 
**text** | **str** | The text content of the post. | 
**author** | [**GetPostsList200ResponseDataInnerAuthor**](GetPostsList200ResponseDataInnerAuthor.md) |  | 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | List of post attachments. | 
**created_at** | **str** | The creation date of the post. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**title** | **str** | The title of the post. | [optional] 
**user_reacted** | [**GetPostsList200ResponseDataInnerQuotedPostUserReacted**](GetPostsList200ResponseDataInnerQuotedPostUserReacted.md) |  | 
**permissions** | [**GetPostsList200ResponseDataInnerPermissions**](GetPostsList200ResponseDataInnerPermissions.md) |  | 
**reactions_counter** | [**List[GetMessagesList200ResponseDataInnerReactionsCounterInner]**](GetMessagesList200ResponseDataInnerReactionsCounterInner.md) | A list of reactions to the element. | 
**comments_counter** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**reposts_counter** | **float** | The number of reposts of the post. &#x60;null&#x60; if counter is hidden. | 
**poll** | [**GetPostsList200ResponseDataInnerPoll**](GetPostsList200ResponseDataInnerPoll.md) |  | [optional] 
**event** | [**GetPostsList200ResponseDataInnerEvent**](GetPostsList200ResponseDataInnerEvent.md) |  | [optional] 
**analytics** | [**GetPostsList200ResponseDataInnerAnalytics**](GetPostsList200ResponseDataInnerAnalytics.md) |  | [optional] 
**is_repost** | **bool** | &#x60;true&#x60; if this post is reposted by someone without quote. Quoted post does not qualify as a repost. | 
**reposted_by** | [**GetPostsList200ResponseDataInnerRepostedBy**](GetPostsList200ResponseDataInnerRepostedBy.md) |  | [optional] 
**quoted_post** | [**GetPostsList200ResponseDataInnerQuotedPost**](GetPostsList200ResponseDataInnerQuotedPost.md) |  | [optional] 

## Example

```python
from unipile.models.get_user_comments_list200_response_data_inner_parent_post import GetUserCommentsList200ResponseDataInnerParentPost

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserCommentsList200ResponseDataInnerParentPost from a JSON string
get_user_comments_list200_response_data_inner_parent_post_instance = GetUserCommentsList200ResponseDataInnerParentPost.from_json(json)
# print the JSON string representation of the object
print(GetUserCommentsList200ResponseDataInnerParentPost.to_json())

# convert the object into a dict
get_user_comments_list200_response_data_inner_parent_post_dict = get_user_comments_list200_response_data_inner_parent_post_instance.to_dict()
# create an instance of GetUserCommentsList200ResponseDataInnerParentPost from a dict
get_user_comments_list200_response_data_inner_parent_post_from_dict = GetUserCommentsList200ResponseDataInnerParentPost.from_dict(get_user_comments_list200_response_data_inner_parent_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


