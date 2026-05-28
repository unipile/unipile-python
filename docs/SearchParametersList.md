# SearchParametersList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[SearchParametersListDataInner]**](SearchParametersListDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.search_parameters_list import SearchParametersList

# TODO update the JSON string below
json = "{}"
# create an instance of SearchParametersList from a JSON string
search_parameters_list_instance = SearchParametersList.from_json(json)
# print the JSON string representation of the object
print(SearchParametersList.to_json())

# convert the object into a dict
search_parameters_list_dict = search_parameters_list_instance.to_dict()
# create an instance of SearchParametersList from a dict
search_parameters_list_from_dict = SearchParametersList.from_dict(search_parameters_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


