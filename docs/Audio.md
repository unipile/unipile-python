# Audio


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the attachment. | 
**file_size** | **float** | The size of the attachment in bytes. | [optional] 
**is_inline** | **bool** | Is the attachment inline in the content. | 
**content_id** | **str** | Reserved for email attachments. The Content-ID (CID) used to reference the attachment inline in the email HTML body via &#x60;cid:&#x60;. Provided without the surrounding angle brackets. | [optional] 
**is_unavailable** | **bool** | The attachment is not available for download because it was removed from provider servers. | [optional] 
**mimetype** | **str** | The MIME type of the attachment. | 
**url** | **str** | The URL to download the attachment. | 
**url_expires_at** | **str** | The URL expiration timestamp. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**content** | **str** | The file content encoded as base64, when available directly without an additional download. | [optional] 
**type** | **str** |  | 
**duration** | **float** | The duration of the audio in seconds. | [optional] 
**voice_note** | **bool** | The audio is a voice note (should be displayed differently) | 

## Example

```python
from unipile.models.audio import Audio

# TODO update the JSON string below
json = "{}"
# create an instance of Audio from a JSON string
audio_instance = Audio.from_json(json)
# print the JSON string representation of the object
print(Audio.to_json())

# convert the object into a dict
audio_dict = audio_instance.to_dict()
# create an instance of Audio from a dict
audio_from_dict = Audio.from_dict(audio_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


