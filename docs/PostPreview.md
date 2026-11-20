# PostPreview


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the post for the provider. | 
**share_url** | **str** | The URL to share the post. | [optional] 
**text** | **str** | The text content of the post. | [optional] 
**attachments** | [**List[PostPreviewAttachmentsInner]**](PostPreviewAttachmentsInner.md) | Attachments of the parent post (e.g. post image). | [optional] 
**author** | [**PostAuthor**](PostAuthor.md) |  | [optional] 

## Example

```python
from unipile.models.post_preview import PostPreview

# TODO update the JSON string below
json = "{}"
# create an instance of PostPreview from a JSON string
post_preview_instance = PostPreview.from_json(json)
# print the JSON string representation of the object
print(PostPreview.to_json())

# convert the object into a dict
post_preview_dict = post_preview_instance.to_dict()
# create an instance of PostPreview from a dict
post_preview_from_dict = PostPreview.from_dict(post_preview_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


