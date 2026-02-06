# PerformClassicSearchFromUrl200ResponseAnyOf2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PerformClassicSearchFromUrl200ResponseAnyOf2DataInner]**](PerformClassicSearchFromUrl200ResponseAnyOf2DataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.perform_classic_search_from_url200_response_any_of2 import PerformClassicSearchFromUrl200ResponseAnyOf2

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOf2 from a JSON string
perform_classic_search_from_url200_response_any_of2_instance = PerformClassicSearchFromUrl200ResponseAnyOf2.from_json(json)
# print the JSON string representation of the object
print(PerformClassicSearchFromUrl200ResponseAnyOf2.to_json())

# convert the object into a dict
perform_classic_search_from_url200_response_any_of2_dict = perform_classic_search_from_url200_response_any_of2_instance.to_dict()
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOf2 from a dict
perform_classic_search_from_url200_response_any_of2_from_dict = PerformClassicSearchFromUrl200ResponseAnyOf2.from_dict(perform_classic_search_from_url200_response_any_of2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


