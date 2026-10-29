# EmailFile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content** | **str** | Content of the file encoded as base64. For large files, prefer using multipart, learn more here: https://developer.unipile.com/v2.0/reference/api-usage#sending-files | 
**content_type** | **str** | &lt;a href&#x3D;\&quot;https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types/Common_types\&quot;&gt;MIME type&lt;/a&gt; of the file. | 
**filename** | **str** | Name of the file (including extension). | 
**metadata** | [**UpdateChatRequestPictureMetadata**](UpdateChatRequestPictureMetadata.md) |  | [optional] 
**content_id** | **str** | The Content-ID (CID) to give to the file, without the surrounding angle brackets. When set, the file is sent as an inline attachment and can be referenced from the HTML content with &#x60;cid:&lt;content_id&gt;&#x60;, for example &#x60;&lt;img src&#x3D;\&quot;cid:my-logo\&quot;&gt;&#x60;. | [optional] 

## Example

```python
from unipile.models.email_file import EmailFile

# TODO update the JSON string below
json = "{}"
# create an instance of EmailFile from a JSON string
email_file_instance = EmailFile.from_json(json)
# print the JSON string representation of the object
print(EmailFile.to_json())

# convert the object into a dict
email_file_dict = email_file_instance.to_dict()
# create an instance of EmailFile from a dict
email_file_from_dict = EmailFile.from_dict(email_file_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


