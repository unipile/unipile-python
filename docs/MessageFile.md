# MessageFile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content** | **str** | Content of the file encoded as base64. | 
**content_type** | **str** | &lt;a href&#x3D;\&quot;https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types/Common_types\&quot;&gt;MIME type&lt;/a&gt; of the file. | 
**filename** | **str** | Name of the file (including extension). | 
**metadata** | [**MessageFileAllOfMetadata**](MessageFileAllOfMetadata.md) |  | [optional] 
**send_mode** | **str** | Defines how the attachment should be sent, if the provider supports multiple modes.             Omitted: use the provider’s native default behavior.             - &#x60;file&#x60; send as a regular uploaded file.             - &#x60;native&#x60; send as a native media (displayed picture, voice note, recorded video, etc.) | [optional] [default to 'native']

## Example

```python
from unipile.models.message_file import MessageFile

# TODO update the JSON string below
json = "{}"
# create an instance of MessageFile from a JSON string
message_file_instance = MessageFile.from_json(json)
# print the JSON string representation of the object
print(MessageFile.to_json())

# convert the object into a dict
message_file_dict = message_file_instance.to_dict()
# create an instance of MessageFile from a dict
message_file_from_dict = MessageFile.from_dict(message_file_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


