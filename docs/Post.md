# Post


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the post for the provider. | 
**share_url** | **str** | The URL to share the post. | 
**created_at** | **str** | The creation date of the post. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**title** | **str** | The title of the post. | [optional] 
**text** | **str** | The text content of the post. | 
**user_reacted** | [**PostUserReacted**](PostUserReacted.md) |  | 
**permissions** | [**PostPermissions**](PostPermissions.md) |  | 
**reactions_counter** | [**List[MessageReactionsCounterInner]**](MessageReactionsCounterInner.md) | A list of reactions to the element. | 
**comments_counter** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**reposts_counter** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**poll** | [**PostPoll**](PostPoll.md) |  | [optional] 
**event** | [**PostEvent**](PostEvent.md) |  | [optional] 
**attachments** | [**List[MessageQuotedAttachmentsInner]**](MessageQuotedAttachmentsInner.md) | List of post attachments. | 
**analytics** | [**PostAnalytics**](PostAnalytics.md) |  | [optional] 
**is_repost** | **bool** | &#x60;true&#x60; if this post is reposted by someone without quote. Quoted post does not qualify as a repost. | 
**author** | [**PostAuthor**](PostAuthor.md) |  | 
**reposted_by** | [**PostRepostedBy**](PostRepostedBy.md) |  | [optional] 
**quoted_post** | [**PostQuotedPost**](PostQuotedPost.md) |  | [optional] 
**specifics** | [**PostSpecifics**](PostSpecifics.md) |  | [optional] 

## Example

```python
from unipile.models.post import Post

# TODO update the JSON string below
json = "{}"
# create an instance of Post from a JSON string
post_instance = Post.from_json(json)
# print the JSON string representation of the object
print(Post.to_json())

# convert the object into a dict
post_dict = post_instance.to_dict()
# create an instance of Post from a dict
post_from_dict = Post.from_dict(post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


