# UpdateChatRequestPictureMetadata

Metadata of the the file.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**duration** | **float** | Duration of the media file. | [optional] 
**waveform** | **List[int]** | Waveform of an audio file sent as a voice note, as a list of up to 64 amplitude values between 0 and 100. When omitted, it is computed from the audio file if the provider displays one. | [optional] 

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


