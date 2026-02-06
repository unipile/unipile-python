# SaveSalesAccountToListRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**company_id** | **str** | The ID of the Company to be saved as Account to the List. | 

## Example

```python
from unipile.models.save_sales_account_to_list_request import SaveSalesAccountToListRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SaveSalesAccountToListRequest from a JSON string
save_sales_account_to_list_request_instance = SaveSalesAccountToListRequest.from_json(json)
# print the JSON string representation of the object
print(SaveSalesAccountToListRequest.to_json())

# convert the object into a dict
save_sales_account_to_list_request_dict = save_sales_account_to_list_request_instance.to_dict()
# create an instance of SaveSalesAccountToListRequest from a dict
save_sales_account_to_list_request_from_dict = SaveSalesAccountToListRequest.from_dict(save_sales_account_to_list_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


