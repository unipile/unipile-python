# AddPostComment201Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the comment. | 
**thread_id** | **str** | The ID of the thread if this is a reply to another comment. | [optional] 
**author** | [**GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender**](GetChatsList200ResponseDataInnerLastMessageAnyOf1Sender.md) |  | 
**created_at** | **str** | The creation date of the comment. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**text** | **str** | The text content of the comment. | 
**attachments** | [**List[GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner]**](GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner.md) | List of comment attachments. | 
**is_sender** | **bool** | Is the current user the sender of the comment. | 
**can_reply** | **bool** | Whether the current user can reply to the comment or not. | 
**can_react** | **bool** | Whether the current user can react to the comment or not. | 
**reply_counter** | **float** | The number of replies to the comment. | 
**impressions_counter** | **float** | The number of impressions of the comment. | [optional] 
**reactions_counter** | [**List[GetChatsList200ResponseDataInnerLastMessageAnyOf1ReactionsCounterInner]**](GetChatsList200ResponseDataInnerLastMessageAnyOf1ReactionsCounterInner.md) | A list of reactions to the element. | 

## Example

```python
from unipile.models.add_post_comment201_response import AddPostComment201Response

# TODO update the JSON string below
json = "{}"
# create an instance of AddPostComment201Response from a JSON string
add_post_comment201_response_instance = AddPostComment201Response.from_json(json)
# print the JSON string representation of the object
print(AddPostComment201Response.to_json())

# convert the object into a dict
add_post_comment201_response_dict = add_post_comment201_response_instance.to_dict()
# create an instance of AddPostComment201Response from a dict
add_post_comment201_response_from_dict = AddPostComment201Response.from_dict(add_post_comment201_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


