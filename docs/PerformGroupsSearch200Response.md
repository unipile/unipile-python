# PerformGroupsSearch200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PerformGroupsSearch200ResponseDataInner]**](PerformGroupsSearch200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the provider. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.perform_groups_search200_response import PerformGroupsSearch200Response

# TODO update the JSON string below
json = "{}"
# create an instance of PerformGroupsSearch200Response from a JSON string
perform_groups_search200_response_instance = PerformGroupsSearch200Response.from_json(json)
# print the JSON string representation of the object
print(PerformGroupsSearch200Response.to_json())

# convert the object into a dict
perform_groups_search200_response_dict = perform_groups_search200_response_instance.to_dict()
# create an instance of PerformGroupsSearch200Response from a dict
perform_groups_search200_response_from_dict = PerformGroupsSearch200Response.from_dict(perform_groups_search200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


