# PerformClassicSearchFromUrl200ResponseAnyOf1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PerformClassicSearchFromUrl200ResponseAnyOf1DataInner]**](PerformClassicSearchFromUrl200ResponseAnyOf1DataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.perform_classic_search_from_url200_response_any_of1 import PerformClassicSearchFromUrl200ResponseAnyOf1

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOf1 from a JSON string
perform_classic_search_from_url200_response_any_of1_instance = PerformClassicSearchFromUrl200ResponseAnyOf1.from_json(json)
# print the JSON string representation of the object
print(PerformClassicSearchFromUrl200ResponseAnyOf1.to_json())

# convert the object into a dict
perform_classic_search_from_url200_response_any_of1_dict = perform_classic_search_from_url200_response_any_of1_instance.to_dict()
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOf1 from a dict
perform_classic_search_from_url200_response_any_of1_from_dict = PerformClassicSearchFromUrl200ResponseAnyOf1.from_dict(perform_classic_search_from_url200_response_any_of1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


