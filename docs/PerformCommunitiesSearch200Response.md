# PerformCommunitiesSearch200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PerformCommunitiesSearch200ResponseDataInner]**](PerformCommunitiesSearch200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the provider. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.perform_communities_search200_response import PerformCommunitiesSearch200Response

# TODO update the JSON string below
json = "{}"
# create an instance of PerformCommunitiesSearch200Response from a JSON string
perform_communities_search200_response_instance = PerformCommunitiesSearch200Response.from_json(json)
# print the JSON string representation of the object
print(PerformCommunitiesSearch200Response.to_json())

# convert the object into a dict
perform_communities_search200_response_dict = perform_communities_search200_response_instance.to_dict()
# create an instance of PerformCommunitiesSearch200Response from a dict
perform_communities_search200_response_from_dict = PerformCommunitiesSearch200Response.from_dict(perform_communities_search200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


