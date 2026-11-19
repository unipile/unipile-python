# PostPreviewAttachmentsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**type** | **str** |  | 
**url** | **str** | The URL of the attachment. | 

## Example

```python
from unipile.models.post_preview_attachments_inner import PostPreviewAttachmentsInner

# TODO update the JSON string below
json = "{}"
# create an instance of PostPreviewAttachmentsInner from a JSON string
post_preview_attachments_inner_instance = PostPreviewAttachmentsInner.from_json(json)
# print the JSON string representation of the object
print(PostPreviewAttachmentsInner.to_json())

# convert the object into a dict
post_preview_attachments_inner_dict = post_preview_attachments_inner_instance.to_dict()
# create an instance of PostPreviewAttachmentsInner from a dict
post_preview_attachments_inner_from_dict = PostPreviewAttachmentsInner.from_dict(post_preview_attachments_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


