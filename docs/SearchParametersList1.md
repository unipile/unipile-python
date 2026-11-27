# SearchParametersList1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[SearchParametersList1DataInner]**](SearchParametersList1DataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the provider. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.search_parameters_list1 import SearchParametersList1

# TODO update the JSON string below
json = "{}"
# create an instance of SearchParametersList1 from a JSON string
search_parameters_list1_instance = SearchParametersList1.from_json(json)
# print the JSON string representation of the object
print(SearchParametersList1.to_json())

# convert the object into a dict
search_parameters_list1_dict = search_parameters_list1_instance.to_dict()
# create an instance of SearchParametersList1 from a dict
search_parameters_list1_from_dict = SearchParametersList1.from_dict(search_parameters_list1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


