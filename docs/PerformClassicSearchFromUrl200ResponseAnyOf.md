# PerformClassicSearchFromUrl200ResponseAnyOf


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PerformClassicSearchFromUrl200ResponseAnyOfDataInner]**](PerformClassicSearchFromUrl200ResponseAnyOfDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.perform_classic_search_from_url200_response_any_of import PerformClassicSearchFromUrl200ResponseAnyOf

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOf from a JSON string
perform_classic_search_from_url200_response_any_of_instance = PerformClassicSearchFromUrl200ResponseAnyOf.from_json(json)
# print the JSON string representation of the object
print(PerformClassicSearchFromUrl200ResponseAnyOf.to_json())

# convert the object into a dict
perform_classic_search_from_url200_response_any_of_dict = perform_classic_search_from_url200_response_any_of_instance.to_dict()
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOf from a dict
perform_classic_search_from_url200_response_any_of_from_dict = PerformClassicSearchFromUrl200ResponseAnyOf.from_dict(perform_classic_search_from_url200_response_any_of_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


