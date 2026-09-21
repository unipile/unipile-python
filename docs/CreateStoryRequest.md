# CreateStoryRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attachment** | [**SendEmailRequestAttachmentsInner**](SendEmailRequestAttachmentsInner.md) |  | 
**text** | **str** | Optional caption for the story. User mentions can be added by inserting an @ followed by the ID or public identifier of the user (example: @JohnDoe), if supported by the provider. | [optional] 
**specifics** | [**CreateStoryRequestSpecifics**](CreateStoryRequestSpecifics.md) |  | [optional] 

## Example

```python
from unipile.models.create_story_request import CreateStoryRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateStoryRequest from a JSON string
create_story_request_instance = CreateStoryRequest.from_json(json)
# print the JSON string representation of the object
print(CreateStoryRequest.to_json())

# convert the object into a dict
create_story_request_dict = create_story_request_instance.to_dict()
# create an instance of CreateStoryRequest from a dict
create_story_request_from_dict = CreateStoryRequest.from_dict(create_story_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


