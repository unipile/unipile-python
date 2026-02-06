# GetPost200Response


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
**is_repost** | **bool** | &#x60;true&#x60; if this post is reposted by someone without quote. Quoted post does not qualify as a repost. | 
**reposted_by** | [**GetPostsList200ResponseDataInnerRepostedBy**](GetPostsList200ResponseDataInnerRepostedBy.md) |  | [optional] 
**quoted_post** | [**GetPostsList200ResponseDataInnerQuotedPost**](GetPostsList200ResponseDataInnerQuotedPost.md) |  | [optional] 

## Example

```python
from unipile.models.get_post200_response import GetPost200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetPost200Response from a JSON string
get_post200_response_instance = GetPost200Response.from_json(json)
# print the JSON string representation of the object
print(GetPost200Response.to_json())

# convert the object into a dict
get_post200_response_dict = get_post200_response_instance.to_dict()
# create an instance of GetPost200Response from a dict
get_post200_response_from_dict = GetPost200Response.from_dict(get_post200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


