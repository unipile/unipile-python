# Loading

The authentication is continuing in the background and requires no user input.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 

## Example

```python
from unipile.models.loading import Loading

# TODO update the JSON string below
json = "{}"
# create an instance of Loading from a JSON string
loading_instance = Loading.from_json(json)
# print the JSON string representation of the object
print(Loading.to_json())

# convert the object into a dict
loading_dict = loading_instance.to_dict()
# create an instance of Loading from a dict
loading_from_dict = Loading.from_dict(loading_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


