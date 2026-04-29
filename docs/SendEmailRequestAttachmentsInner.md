# SendEmailRequestAttachmentsInner

A file to be uploaded.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content** | **str** | Content of the file encoded as base64. For large files, prefer using multipart, learn more here: https://developer.unipile.com/v2.0/reference/api-usage#sending-files | 
**content_type** | **str** | &lt;a href&#x3D;\&quot;https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types/Common_types\&quot;&gt;MIME type&lt;/a&gt; of the file. | 
**filename** | **str** | Name of the file (including extension). | 
**metadata** | [**MessageFileAllOfMetadata**](MessageFileAllOfMetadata.md) |  | [optional] 

## Example

```python
from unipile.models.send_email_request_attachments_inner import SendEmailRequestAttachmentsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendEmailRequestAttachmentsInner from a JSON string
send_email_request_attachments_inner_instance = SendEmailRequestAttachmentsInner.from_json(json)
# print the JSON string representation of the object
print(SendEmailRequestAttachmentsInner.to_json())

# convert the object into a dict
send_email_request_attachments_inner_dict = send_email_request_attachments_inner_instance.to_dict()
# create an instance of SendEmailRequestAttachmentsInner from a dict
send_email_request_attachments_inner_from_dict = SendEmailRequestAttachmentsInner.from_dict(send_email_request_attachments_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


