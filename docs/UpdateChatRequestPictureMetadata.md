# UpdateChatRequestPictureMetadata

Metadata of the the file.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**duration** | **float** | Duration of the media file. | [optional] 

## Example

```python
from unipile.models.update_chat_request_picture_metadata import UpdateChatRequestPictureMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateChatRequestPictureMetadata from a JSON string
update_chat_request_picture_metadata_instance = UpdateChatRequestPictureMetadata.from_json(json)
# print the JSON string representation of the object
print(UpdateChatRequestPictureMetadata.to_json())

# convert the object into a dict
update_chat_request_picture_metadata_dict = update_chat_request_picture_metadata_instance.to_dict()
# create an instance of UpdateChatRequestPictureMetadata from a dict
update_chat_request_picture_metadata_from_dict = UpdateChatRequestPictureMetadata.from_dict(update_chat_request_picture_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


