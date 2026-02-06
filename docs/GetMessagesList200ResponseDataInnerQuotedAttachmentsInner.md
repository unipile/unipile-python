# GetMessagesList200ResponseDataInnerQuotedAttachmentsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the attachment for the provider. | 
**file_size** | **float** | The size of the attachment in bytes. | [optional] 
**is_unavailable** | **bool** | The attachment is not available for download because it was removed from provider servers. | [optional] 
**mimetype** | **str** | The MIME type of the attachment. | 
**url** | **str** | The URL of the shared content. | 
**url_expires_at** | **str** | The URL expiration timestamp. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**content** | **str** | Content of the attachement | [optional] 
**type** | **str** |  | 
**duration** | **float** | The duration of the video in seconds. | [optional] 
**voice_note** | **bool** | The audio is a voice note (should be displayed differently) | 
**size** | [**Video1Size**](Video1Size.md) |  | 
**sticker** | **bool** | The image is a sticker (should be displayed differently) | 
**gif** | **bool** | The video is a GIF (should be displayed differently) | 
**filename** | **str** | The name of the file, including the extension. | 
**media_type** | **str** | The type of content being shared. | 
**author** | **str** | The author of the shared content, if applicable. | [optional] 
**description** | **str** | A brief description of the shared content. | [optional] 

## Example

```python
from unipile.models.get_messages_list200_response_data_inner_quoted_attachments_inner import GetMessagesList200ResponseDataInnerQuotedAttachmentsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMessagesList200ResponseDataInnerQuotedAttachmentsInner from a JSON string
get_messages_list200_response_data_inner_quoted_attachments_inner_instance = GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.from_json(json)
# print the JSON string representation of the object
print(GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.to_json())

# convert the object into a dict
get_messages_list200_response_data_inner_quoted_attachments_inner_dict = get_messages_list200_response_data_inner_quoted_attachments_inner_instance.to_dict()
# create an instance of GetMessagesList200ResponseDataInnerQuotedAttachmentsInner from a dict
get_messages_list200_response_data_inner_quoted_attachments_inner_from_dict = GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.from_dict(get_messages_list200_response_data_inner_quoted_attachments_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


