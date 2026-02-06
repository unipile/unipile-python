# NewExperienceAttachment


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**content** | **str** | Content of the file encoded as base64. | 
**content_type** | **str** | &lt;a href&#x3D;\&quot;https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types/Common_types\&quot;&gt;MIME type&lt;/a&gt; of the file. | 
**filename** | **str** | Name of the file (including extension). | 
**metadata** | [**MessageFileAllOfMetadata**](MessageFileAllOfMetadata.md) |  | [optional] 
**url** | **str** | URL of the link. | 
**thumbnail** | [**SendEmailRequestAttachmentsInner**](SendEmailRequestAttachmentsInner.md) |  | [optional] 

## Example

```python
from unipile.models.new_experience_attachment import NewExperienceAttachment

# TODO update the JSON string below
json = "{}"
# create an instance of NewExperienceAttachment from a JSON string
new_experience_attachment_instance = NewExperienceAttachment.from_json(json)
# print the JSON string representation of the object
print(NewExperienceAttachment.to_json())

# convert the object into a dict
new_experience_attachment_dict = new_experience_attachment_instance.to_dict()
# create an instance of NewExperienceAttachment from a dict
new_experience_attachment_from_dict = NewExperienceAttachment.from_dict(new_experience_attachment_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


