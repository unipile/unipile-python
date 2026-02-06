# GetPostsList200ResponseDataInnerQuotedPost

The post that is quoted in this post.

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
**reactions_counter** | [**List[GetMessagesList200ResponseDataInnerReactionsCounterInner]**](GetMessagesList200ResponseDataInnerReactionsCounterInner.md) | The number of reactions to the element | 
**comments_counter** | **float** |  | 
**reposts_counter** | **float** |  | 
**poll** | [**GetPostsList200ResponseDataInnerPoll**](GetPostsList200ResponseDataInnerPoll.md) |  | [optional] 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | List of post attachments. | 
**analytics** | [**GetPostsList200ResponseDataInnerAnalytics**](GetPostsList200ResponseDataInnerAnalytics.md) |  | [optional] 

## Example

```python
from unipile.models.get_posts_list200_response_data_inner_quoted_post import GetPostsList200ResponseDataInnerQuotedPost

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostsList200ResponseDataInnerQuotedPost from a JSON string
get_posts_list200_response_data_inner_quoted_post_instance = GetPostsList200ResponseDataInnerQuotedPost.from_json(json)
# print the JSON string representation of the object
print(GetPostsList200ResponseDataInnerQuotedPost.to_json())

# convert the object into a dict
get_posts_list200_response_data_inner_quoted_post_dict = get_posts_list200_response_data_inner_quoted_post_instance.to_dict()
# create an instance of GetPostsList200ResponseDataInnerQuotedPost from a dict
get_posts_list200_response_data_inner_quoted_post_from_dict = GetPostsList200ResponseDataInnerQuotedPost.from_dict(get_posts_list200_response_data_inner_quoted_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


