# CustomLink


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | The type of link. | 
**url** | **str** | The URL of the link. | 
**display_on** | **str** | Whether the link should be displayed everywhere or only on the profile. | [optional] [default to 'EVERYWHERE']

## Example

```python
from unipile.models.custom_link import CustomLink

# TODO update the JSON string below
json = "{}"
# create an instance of CustomLink from a JSON string
custom_link_instance = CustomLink.from_json(json)
# print the JSON string representation of the object
print(CustomLink.to_json())

# convert the object into a dict
custom_link_dict = custom_link_instance.to_dict()
# create an instance of CustomLink from a dict
custom_link_from_dict = CustomLink.from_dict(custom_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


