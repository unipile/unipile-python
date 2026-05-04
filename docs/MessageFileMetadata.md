# MessageFileMetadata

Metadata of the the file.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**duration** | **float** | Duration of the media file. | [optional] 

## Example

```python
from unipile.models.message_file_metadata import MessageFileMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of MessageFileMetadata from a JSON string
message_file_metadata_instance = MessageFileMetadata.from_json(json)
# print the JSON string representation of the object
print(MessageFileMetadata.to_json())

# convert the object into a dict
message_file_metadata_dict = message_file_metadata_instance.to_dict()
# create an instance of MessageFileMetadata from a dict
message_file_metadata_from_dict = MessageFileMetadata.from_dict(message_file_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


