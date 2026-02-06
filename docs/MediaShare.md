# MediaShare


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
**media_type** | **str** | The type of content being shared. | 
**author** | **str** | The author of the shared content, if applicable. | [optional] 
**description** | **str** | A brief description of the shared content. | [optional] 

## Example

```python
from unipile.models.media_share import MediaShare

# TODO update the JSON string below
json = "{}"
# create an instance of MediaShare from a JSON string
media_share_instance = MediaShare.from_json(json)
# print the JSON string representation of the object
print(MediaShare.to_json())

# convert the object into a dict
media_share_dict = media_share_instance.to_dict()
# create an instance of MediaShare from a dict
media_share_from_dict = MediaShare.from_dict(media_share_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


