# UpdatePost200ResponseQuotedPost

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
**author** | [**UpdateChat200ResponseParticipantsInnerUser**](UpdateChat200ResponseParticipantsInnerUser.md) |  | 
**user_reacted** | [**GetPostsList200ResponseDataInnerQuotedPostUserReacted**](GetPostsList200ResponseDataInnerQuotedPostUserReacted.md) |  | 
**permissions** | [**GetPostsList200ResponseDataInnerPermissions**](GetPostsList200ResponseDataInnerPermissions.md) |  | 
**reactions_counter** | [**List[GetMessagesList200ResponseDataInnerReactionsCounterInner]**](GetMessagesList200ResponseDataInnerReactionsCounterInner.md) | A list of reactions to the element. | 
**comments_counter** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**reposts_counter** | **float** | The number of reposts of the post. &#x60;null&#x60; if counter is hidden. | 
**poll** | [**GetPostsList200ResponseDataInnerPoll**](GetPostsList200ResponseDataInnerPoll.md) |  | [optional] 
**event** | [**GetPostsList200ResponseDataInnerEvent**](GetPostsList200ResponseDataInnerEvent.md) |  | [optional] 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | List of post attachments. | 
**analytics** | [**GetPostsList200ResponseDataInnerAnalytics**](GetPostsList200ResponseDataInnerAnalytics.md) |  | [optional] 

## Example

```python
from unipile.models.update_post200_response_quoted_post import UpdatePost200ResponseQuotedPost

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePost200ResponseQuotedPost from a JSON string
update_post200_response_quoted_post_instance = UpdatePost200ResponseQuotedPost.from_json(json)
# print the JSON string representation of the object
print(UpdatePost200ResponseQuotedPost.to_json())

# convert the object into a dict
update_post200_response_quoted_post_dict = update_post200_response_quoted_post_instance.to_dict()
# create an instance of UpdatePost200ResponseQuotedPost from a dict
update_post200_response_quoted_post_from_dict = UpdatePost200ResponseQuotedPost.from_dict(update_post200_response_quoted_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


