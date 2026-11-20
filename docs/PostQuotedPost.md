# PostQuotedPost

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
**user_reacted** | [**PostQuotedPostUserReacted**](PostQuotedPostUserReacted.md) |  | 
**permissions** | [**PostPermissions**](PostPermissions.md) |  | 
**reactions_counter** | [**List[MessageReactionsCounterInner]**](MessageReactionsCounterInner.md) | A list of reactions to the element. | 
**comments_counter** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**reposts_counter** | **float** | The number of reposts of the post. &#x60;null&#x60; if counter is hidden. | 
**poll** | [**PostPoll**](PostPoll.md) |  | [optional] 
**event** | [**PostEvent**](PostEvent.md) |  | [optional] 
**attachments** | [**List[MessageQuotedAttachmentsInner]**](MessageQuotedAttachmentsInner.md) | List of post attachments. | 
**analytics** | [**PostAnalytics**](PostAnalytics.md) |  | [optional] 
**author** | [**PostAuthor**](PostAuthor.md) |  | 
**specifics** | [**PostQuotedPostSpecifics**](PostQuotedPostSpecifics.md) |  | [optional] 

## Example

```python
from unipile.models.post_quoted_post import PostQuotedPost

# TODO update the JSON string below
json = "{}"
# create an instance of PostQuotedPost from a JSON string
post_quoted_post_instance = PostQuotedPost.from_json(json)
# print the JSON string representation of the object
print(PostQuotedPost.to_json())

# convert the object into a dict
post_quoted_post_dict = post_quoted_post_instance.to_dict()
# create an instance of PostQuotedPost from a dict
post_quoted_post_from_dict = PostQuotedPost.from_dict(post_quoted_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


