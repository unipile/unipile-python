# GetSalesLeadLists200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**id** | **str** | The ID of the List. | 
**name** | **str** | The name of the List. | 
**description** | **str** | The description of the List. | [optional] 
**items_count** | **float** | The number of items in the List. | 
**last_modified_at** | **str** | The date on which the List was last modified. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**last_viewed_at** | **str** | The date on which the List was last viewed. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 

## Example

```python
from unipile.models.get_sales_lead_lists200_response_data_inner import GetSalesLeadLists200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetSalesLeadLists200ResponseDataInner from a JSON string
get_sales_lead_lists200_response_data_inner_instance = GetSalesLeadLists200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetSalesLeadLists200ResponseDataInner.to_json())

# convert the object into a dict
get_sales_lead_lists200_response_data_inner_dict = get_sales_lead_lists200_response_data_inner_instance.to_dict()
# create an instance of GetSalesLeadLists200ResponseDataInner from a dict
get_sales_lead_lists200_response_data_inner_from_dict = GetSalesLeadLists200ResponseDataInner.from_dict(get_sales_lead_lists200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


