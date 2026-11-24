# Post1


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
**is_repost** | **bool** | &#x60;true&#x60; if this post is reposted by someone without quote. Quoted post does not qualify as a repost. | 
**author** | [**PostAuthor**](PostAuthor.md) |  | 
**reposted_by** | [**PostRepostedBy**](PostRepostedBy.md) |  | [optional] 
**quoted_post** | [**Post1QuotedPost**](Post1QuotedPost.md) |  | [optional] 
**specifics** | [**PostSpecifics**](PostSpecifics.md) |  | [optional] 

## Example

```python
from unipile.models.post1 import Post1

# TODO update the JSON string below
json = "{}"
# create an instance of Post1 from a JSON string
post1_instance = Post1.from_json(json)
# print the JSON string representation of the object
print(Post1.to_json())

# convert the object into a dict
post1_dict = post1_instance.to_dict()
# create an instance of Post1 from a dict
post1_from_dict = Post1.from_dict(post1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


