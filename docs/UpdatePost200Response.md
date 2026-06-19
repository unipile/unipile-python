# UpdatePost200Response


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
**specifics** | **object** |  | [optional] 
**is_repost** | **bool** | &#x60;true&#x60; if this post is reposted by someone without quote. Quoted post does not qualify as a repost. | 
**reposted_by** | [**UpdateChat200ResponseParticipantsInnerUser**](UpdateChat200ResponseParticipantsInnerUser.md) |  | [optional] 
**quoted_post** | [**UpdatePost200ResponseQuotedPost**](UpdatePost200ResponseQuotedPost.md) |  | [optional] 

## Example

```python
from unipile.models.update_post200_response import UpdatePost200Response

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePost200Response from a JSON string
update_post200_response_instance = UpdatePost200Response.from_json(json)
# print the JSON string representation of the object
print(UpdatePost200Response.to_json())

# convert the object into a dict
update_post200_response_dict = update_post200_response_instance.to_dict()
# create an instance of UpdatePost200Response from a dict
update_post200_response_from_dict = UpdatePost200Response.from_dict(update_post200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


