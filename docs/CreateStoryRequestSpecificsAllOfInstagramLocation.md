# CreateStoryRequestSpecificsAllOfInstagramLocation

Location sticker to attach to the story.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the location (from the Search Locations method) to attach as a sticker. | 
**name** | **str** | The display name of the location, rendered as the sticker text. | 

## Example

```python
from unipile.models.create_story_request_specifics_all_of_instagram_location import CreateStoryRequestSpecificsAllOfInstagramLocation

# TODO update the JSON string below
json = "{}"
# create an instance of CreateStoryRequestSpecificsAllOfInstagramLocation from a JSON string
create_story_request_specifics_all_of_instagram_location_instance = CreateStoryRequestSpecificsAllOfInstagramLocation.from_json(json)
# print the JSON string representation of the object
print(CreateStoryRequestSpecificsAllOfInstagramLocation.to_json())

# convert the object into a dict
create_story_request_specifics_all_of_instagram_location_dict = create_story_request_specifics_all_of_instagram_location_instance.to_dict()
# create an instance of CreateStoryRequestSpecificsAllOfInstagramLocation from a dict
create_story_request_specifics_all_of_instagram_location_from_dict = CreateStoryRequestSpecificsAllOfInstagramLocation.from_dict(create_story_request_specifics_all_of_instagram_location_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


