# CreateStoryRequestSpecifics


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**instagram** | [**CreateStoryRequestSpecificsAllOfInstagram**](CreateStoryRequestSpecificsAllOfInstagram.md) |  | [optional] 

## Example

```python
from unipile.models.create_story_request_specifics import CreateStoryRequestSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of CreateStoryRequestSpecifics from a JSON string
create_story_request_specifics_instance = CreateStoryRequestSpecifics.from_json(json)
# print the JSON string representation of the object
print(CreateStoryRequestSpecifics.to_json())

# convert the object into a dict
create_story_request_specifics_dict = create_story_request_specifics_instance.to_dict()
# create an instance of CreateStoryRequestSpecifics from a dict
create_story_request_specifics_from_dict = CreateStoryRequestSpecifics.from_dict(create_story_request_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


