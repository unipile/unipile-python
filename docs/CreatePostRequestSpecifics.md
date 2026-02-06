# CreatePostRequestSpecifics


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**instagram** | [**CreatePostRequestSpecificsAllOfInstagram**](CreatePostRequestSpecificsAllOfInstagram.md) |  | [optional] 

## Example

```python
from unipile.models.create_post_request_specifics import CreatePostRequestSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of CreatePostRequestSpecifics from a JSON string
create_post_request_specifics_instance = CreatePostRequestSpecifics.from_json(json)
# print the JSON string representation of the object
print(CreatePostRequestSpecifics.to_json())

# convert the object into a dict
create_post_request_specifics_dict = create_post_request_specifics_instance.to_dict()
# create an instance of CreatePostRequestSpecifics from a dict
create_post_request_specifics_from_dict = CreatePostRequestSpecifics.from_dict(create_post_request_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


