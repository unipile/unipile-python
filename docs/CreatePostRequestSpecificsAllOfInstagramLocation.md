# CreatePostRequestSpecificsAllOfInstagramLocation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the location to tag the post with. | 
**longitude** | **float** | The longitude of the location to tag the post with. | [optional] 
**latitude** | **float** | The latitude of the location to tag the post with. | [optional] 

## Example

```python
from unipile.models.create_post_request_specifics_all_of_instagram_location import CreatePostRequestSpecificsAllOfInstagramLocation

# TODO update the JSON string below
json = "{}"
# create an instance of CreatePostRequestSpecificsAllOfInstagramLocation from a JSON string
create_post_request_specifics_all_of_instagram_location_instance = CreatePostRequestSpecificsAllOfInstagramLocation.from_json(json)
# print the JSON string representation of the object
print(CreatePostRequestSpecificsAllOfInstagramLocation.to_json())

# convert the object into a dict
create_post_request_specifics_all_of_instagram_location_dict = create_post_request_specifics_all_of_instagram_location_instance.to_dict()
# create an instance of CreatePostRequestSpecificsAllOfInstagramLocation from a dict
create_post_request_specifics_all_of_instagram_location_from_dict = CreatePostRequestSpecificsAllOfInstagramLocation.from_dict(create_post_request_specifics_all_of_instagram_location_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


