# CreateNewExperienceMedia


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **str** | Title of the media. | [optional] 
**description** | **str** | Description of the media. | [optional] 
**type** | **str** |  | 
**attachment** | [**SendEmailRequestAttachmentsInner**](SendEmailRequestAttachmentsInner.md) |  | 
**url** | **str** | URL of the link. | 
**thumbnail** | [**SendEmailRequestAttachmentsInner**](SendEmailRequestAttachmentsInner.md) |  | [optional] 

## Example

```python
from unipile.models.create_new_experience_media import CreateNewExperienceMedia

# TODO update the JSON string below
json = "{}"
# create an instance of CreateNewExperienceMedia from a JSON string
create_new_experience_media_instance = CreateNewExperienceMedia.from_json(json)
# print the JSON string representation of the object
print(CreateNewExperienceMedia.to_json())

# convert the object into a dict
create_new_experience_media_dict = create_new_experience_media_instance.to_dict()
# create an instance of CreateNewExperienceMedia from a dict
create_new_experience_media_from_dict = CreateNewExperienceMedia.from_dict(create_new_experience_media_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


