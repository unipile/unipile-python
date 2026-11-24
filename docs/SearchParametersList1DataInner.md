# SearchParametersList1DataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The identifier of the search parameter. | 
**name** | **str** | The display name of the search parameter. | 
**metadata** | [**SearchParametersList1DataInnerMetadata**](SearchParametersList1DataInnerMetadata.md) |  | [optional] 

## Example

```python
from unipile.models.search_parameters_list1_data_inner import SearchParametersList1DataInner

# TODO update the JSON string below
json = "{}"
# create an instance of SearchParametersList1DataInner from a JSON string
search_parameters_list1_data_inner_instance = SearchParametersList1DataInner.from_json(json)
# print the JSON string representation of the object
print(SearchParametersList1DataInner.to_json())

# convert the object into a dict
search_parameters_list1_data_inner_dict = search_parameters_list1_data_inner_instance.to_dict()
# create an instance of SearchParametersList1DataInner from a dict
search_parameters_list1_data_inner_from_dict = SearchParametersList1DataInner.from_dict(search_parameters_list1_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


