# CreateStory201Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the story for the provider. | 
**provider_id** | **str** | The story&#39;s raw provider-native identifier. | 
**media_type** | **str** | The type of media attached to the story. | 
**created_at** | **str** | The creation date of the story. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**expires_at** | **str** | The expiration date of the story (~24h after creation, if supported by the provider). Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 

## Example

```python
from unipile.models.create_story201_response import CreateStory201Response

# TODO update the JSON string below
json = "{}"
# create an instance of CreateStory201Response from a JSON string
create_story201_response_instance = CreateStory201Response.from_json(json)
# print the JSON string representation of the object
print(CreateStory201Response.to_json())

# convert the object into a dict
create_story201_response_dict = create_story201_response_instance.to_dict()
# create an instance of CreateStory201Response from a dict
create_story201_response_from_dict = CreateStory201Response.from_dict(create_story201_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


