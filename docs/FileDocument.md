# FileDocument


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the attachment for the provider. | 
**file_size** | **float** | The size of the attachment in bytes. | [optional] 
**is_unavailable** | **bool** | The attachment is not available for download because it was removed from provider servers. | [optional] 
**mimetype** | **str** | The MIME type of the attachment. | 
**url** | **str** | The URL to download the attachment. | 
**url_expires_at** | **str** | The URL expiration timestamp. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**content** | **str** | Content of the attachement | [optional] 
**type** | **str** |  | 
**filename** | **str** | The name of the file, including the extension. | 

## Example

```python
from unipile.models.file_document import FileDocument

# TODO update the JSON string below
json = "{}"
# create an instance of FileDocument from a JSON string
file_document_instance = FileDocument.from_json(json)
# print the JSON string representation of the object
print(FileDocument.to_json())

# convert the object into a dict
file_document_dict = file_document_instance.to_dict()
# create an instance of FileDocument from a dict
file_document_from_dict = FileDocument.from_dict(file_document_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


