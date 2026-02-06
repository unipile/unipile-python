# PerformSalesSearchFromUrl200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[AccountListDataInner]**](AccountListDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.perform_sales_search_from_url200_response import PerformSalesSearchFromUrl200Response

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesSearchFromUrl200Response from a JSON string
perform_sales_search_from_url200_response_instance = PerformSalesSearchFromUrl200Response.from_json(json)
# print the JSON string representation of the object
print(PerformSalesSearchFromUrl200Response.to_json())

# convert the object into a dict
perform_sales_search_from_url200_response_dict = perform_sales_search_from_url200_response_instance.to_dict()
# create an instance of PerformSalesSearchFromUrl200Response from a dict
perform_sales_search_from_url200_response_from_dict = PerformSalesSearchFromUrl200Response.from_dict(perform_sales_search_from_url200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


