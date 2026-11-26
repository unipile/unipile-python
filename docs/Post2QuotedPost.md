# Post2QuotedPost

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
**author** | [**Post2Author**](Post2Author.md) |  | 
**user_reacted** | [**PostQuotedPostUserReacted**](PostQuotedPostUserReacted.md) |  | 
**permissions** | [**PostPermissions**](PostPermissions.md) |  | 
**reactions_counter** | [**List[MessageReactionsCounterInner]**](MessageReactionsCounterInner.md) | A list of reactions to the element. | 
**comments_counter** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**reposts_counter** | **float** | The number of reposts of the post. &#x60;null&#x60; if counter is hidden. | 
**poll** | [**PostPoll**](PostPoll.md) |  | [optional] 
**event** | [**PostEvent**](PostEvent.md) |  | [optional] 
**attachments** | [**List[MessageQuotedAttachmentsInner]**](MessageQuotedAttachmentsInner.md) | List of post attachments. | 
**analytics** | [**PostAnalytics**](PostAnalytics.md) |  | [optional] 
**specifics** | **object** | Object containing provider-specific post data. | [optional] 

## Example

```python
from unipile.models.post2_quoted_post import Post2QuotedPost

# TODO update the JSON string below
json = "{}"
# create an instance of Post2QuotedPost from a JSON string
post2_quoted_post_instance = Post2QuotedPost.from_json(json)
# print the JSON string representation of the object
print(Post2QuotedPost.to_json())

# convert the object into a dict
post2_quoted_post_dict = post2_quoted_post_instance.to_dict()
# create an instance of Post2QuotedPost from a dict
post2_quoted_post_from_dict = Post2QuotedPost.from_dict(post2_quoted_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


