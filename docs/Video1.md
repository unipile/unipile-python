# Video1


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
**duration** | **float** | The duration of the video in seconds. | [optional] 
**size** | [**Video1Size**](Video1Size.md) |  | 
**gif** | **bool** | The video is a GIF (should be displayed differently) | 

## Example

```python
from unipile.models.video1 import Video1

# TODO update the JSON string below
json = "{}"
# create an instance of Video1 from a JSON string
video1_instance = Video1.from_json(json)
# print the JSON string representation of the object
print(Video1.to_json())

# convert the object into a dict
video1_dict = video1_instance.to_dict()
# create an instance of Video1 from a dict
video1_from_dict = Video1.from_dict(video1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


