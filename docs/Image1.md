# Image1


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
**size** | [**Image1Size**](Image1Size.md) |  | [optional] 
**sticker** | **bool** | The image is a sticker (should be displayed differently) | 

## Example

```python
from unipile.models.image1 import Image1

# TODO update the JSON string below
json = "{}"
# create an instance of Image1 from a JSON string
image1_instance = Image1.from_json(json)
# print the JSON string representation of the object
print(Image1.to_json())

# convert the object into a dict
image1_dict = image1_instance.to_dict()
# create an instance of Image1 from a dict
image1_from_dict = Image1.from_dict(image1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


