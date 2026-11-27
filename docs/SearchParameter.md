# SearchParameter

A value to give to a search filter.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;SearchParameter&#x60;. | 
**id** | **str** | The ID to give to the matching filter of a search. | 
**name** | **str** | The display name of the search parameter. | 
**picture_url** | **str** | The URL of the picture of the search parameter. | [optional] 

## Example

```python
from unipile.models.search_parameter import SearchParameter

# TODO update the JSON string below
json = "{}"
# create an instance of SearchParameter from a JSON string
search_parameter_instance = SearchParameter.from_json(json)
# print the JSON string representation of the object
print(SearchParameter.to_json())

# convert the object into a dict
search_parameter_dict = search_parameter_instance.to_dict()
# create an instance of SearchParameter from a dict
search_parameter_from_dict = SearchParameter.from_dict(search_parameter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


