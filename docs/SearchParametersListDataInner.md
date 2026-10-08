# SearchParametersListDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The identifier of the search parameter. | 
**name** | **str** | The display name of the search parameter. | 
**metadata** | [**SearchParametersListDataInnerMetadata**](SearchParametersListDataInnerMetadata.md) |  | [optional] 

## Example

```python
from unipile.models.search_parameters_list_data_inner import SearchParametersListDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of SearchParametersListDataInner from a JSON string
search_parameters_list_data_inner_instance = SearchParametersListDataInner.from_json(json)
# print the JSON string representation of the object
print(SearchParametersListDataInner.to_json())

# convert the object into a dict
search_parameters_list_data_inner_dict = search_parameters_list_data_inner_instance.to_dict()
# create an instance of SearchParametersListDataInner from a dict
search_parameters_list_data_inner_from_dict = SearchParametersListDataInner.from_dict(search_parameters_list_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


