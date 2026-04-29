# GetUserCommentsList200ResponseDataInnerParentPost

Based on the provider, more or less data is returned.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the post for the provider. | 
**share_url** | **str** | The URL to share the post. | [optional] 
**text** | **str** | The text content of the post. | [optional] 
**author** | [**GetPostsList200ResponseDataInnerAuthor**](GetPostsList200ResponseDataInnerAuthor.md) |  | [optional] 
**attachments** | [**List[GetUserCommentsList200ResponseDataInnerParentPostAttachmentsInner]**](GetUserCommentsList200ResponseDataInnerParentPostAttachmentsInner.md) | Attachments of the parent post (e.g. post image). | [optional] 

## Example

```python
from unipile.models.get_user_comments_list200_response_data_inner_parent_post import GetUserCommentsList200ResponseDataInnerParentPost

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserCommentsList200ResponseDataInnerParentPost from a JSON string
get_user_comments_list200_response_data_inner_parent_post_instance = GetUserCommentsList200ResponseDataInnerParentPost.from_json(json)
# print the JSON string representation of the object
print(GetUserCommentsList200ResponseDataInnerParentPost.to_json())

# convert the object into a dict
get_user_comments_list200_response_data_inner_parent_post_dict = get_user_comments_list200_response_data_inner_parent_post_instance.to_dict()
# create an instance of GetUserCommentsList200ResponseDataInnerParentPost from a dict
get_user_comments_list200_response_data_inner_parent_post_from_dict = GetUserCommentsList200ResponseDataInnerParentPost.from_dict(get_user_comments_list200_response_data_inner_parent_post_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


