# SaveSalesLeadToListRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | The ID of the User to be saved as Lead to the List. | 

## Example

```python
from unipile.models.save_sales_lead_to_list_request import SaveSalesLeadToListRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SaveSalesLeadToListRequest from a JSON string
save_sales_lead_to_list_request_instance = SaveSalesLeadToListRequest.from_json(json)
# print the JSON string representation of the object
print(SaveSalesLeadToListRequest.to_json())

# convert the object into a dict
save_sales_lead_to_list_request_dict = save_sales_lead_to_list_request_instance.to_dict()
# create an instance of SaveSalesLeadToListRequest from a dict
save_sales_lead_to_list_request_from_dict = SaveSalesLeadToListRequest.from_dict(save_sales_lead_to_list_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


