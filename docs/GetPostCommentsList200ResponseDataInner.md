# GetPostCommentsList200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the comment. | 
**thread_id** | **str** | The ID of the thread if this is a reply to another comment. | [optional] 
**author** | [**GetPostCommentsList200ResponseDataInnerAuthor**](GetPostCommentsList200ResponseDataInnerAuthor.md) |  | 
**created_at** | **str** | The creation date of the comment. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**text** | **str** | The text content of the comment. | 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | List of comment attachments. | 
**is_sender** | **bool** | Is the current user the sender of the comment. | 
**can_reply** | **bool** | Whether the current user can reply to the comment or not. | 
**can_react** | **bool** | Whether the current user can react to the comment or not. | 
**reply_counter** | **float** | The number of replies to the comment. | 
**impressions_counter** | **float** | The number of impressions of the comment. | [optional] 
**reactions_counter** | [**List[GetMessagesList200ResponseDataInnerReactionsCounterInner]**](GetMessagesList200ResponseDataInnerReactionsCounterInner.md) | A list of reactions to the element. | 

## Example

```python
from unipile.models.get_post_comments_list200_response_data_inner import GetPostCommentsList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostCommentsList200ResponseDataInner from a JSON string
get_post_comments_list200_response_data_inner_instance = GetPostCommentsList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetPostCommentsList200ResponseDataInner.to_json())

# convert the object into a dict
get_post_comments_list200_response_data_inner_dict = get_post_comments_list200_response_data_inner_instance.to_dict()
# create an instance of GetPostCommentsList200ResponseDataInner from a dict
get_post_comments_list200_response_data_inner_from_dict = GetPostCommentsList200ResponseDataInner.from_dict(get_post_comments_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


