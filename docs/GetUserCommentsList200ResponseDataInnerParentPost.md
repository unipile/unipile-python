# GetUserCommentsList200ResponseDataInnerParentPost


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the post for the provider. | 
**share_url** | **str** | The URL to share the post. | 
**text** | **str** | The text content of the post. | 
**attachments** | [**List[MessageQuotedAttachmentsInner]**](MessageQuotedAttachmentsInner.md) | List of post attachments. | 
**author** | [**PostAuthor**](PostAuthor.md) |  | 
**created_at** | **str** | The creation date of the post. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**title** | **str** | The title of the post. | [optional] 
**user_reacted** | [**PostQuotedPostUserReacted**](PostQuotedPostUserReacted.md) |  | 
**permissions** | [**PostPermissions**](PostPermissions.md) |  | 
**reactions_counter** | [**List[MessageReactionsCounterInner]**](MessageReactionsCounterInner.md) | A list of reactions to the element. | 
**comments_counter** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**reposts_counter** | **float** | The number of reposts of the post. &#x60;null&#x60; if counter is hidden. | 
**poll** | [**PostPoll**](PostPoll.md) |  | [optional] 
**event** | [**PostEvent**](PostEvent.md) |  | [optional] 
**analytics** | [**PostAnalytics**](PostAnalytics.md) |  | [optional] 
**is_repost** | **bool** | &#x60;true&#x60; if this post is reposted by someone without quote. Quoted post does not qualify as a repost. | 
**reposted_by** | [**PostRepostedBy**](PostRepostedBy.md) |  | [optional] 
**quoted_post** | [**Post1QuotedPost**](Post1QuotedPost.md) |  | [optional] 
**specifics** | [**PostSpecifics**](PostSpecifics.md) |  | [optional] 

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


