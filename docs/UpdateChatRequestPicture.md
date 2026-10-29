# UpdateChatRequestPicture

A file to be uploaded.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content** | **str** | Content of the file encoded as base64. For large files, prefer using multipart, learn more here: https://developer.unipile.com/v2.0/reference/api-usage#sending-files | 
**content_type** | **str** | &lt;a href&#x3D;\&quot;https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types/Common_types\&quot;&gt;MIME type&lt;/a&gt; of the file. | 
**filename** | **str** | Name of the file (including extension). | 
**metadata** | [**UpdateChatRequestPictureMetadata**](UpdateChatRequestPictureMetadata.md) |  | [optional] 

## Example

```python
from unipile.models.update_chat_request_picture import UpdateChatRequestPicture

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateChatRequestPicture from a JSON string
update_chat_request_picture_instance = UpdateChatRequestPicture.from_json(json)
# print the JSON string representation of the object
print(UpdateChatRequestPicture.to_json())

# convert the object into a dict
update_chat_request_picture_dict = update_chat_request_picture_instance.to_dict()
# create an instance of UpdateChatRequestPicture from a dict
update_chat_request_picture_from_dict = UpdateChatRequestPicture.from_dict(update_chat_request_picture_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


