# BrowseSalesLeadListRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**spotlight** | **str** | Smart filter to help you prioritize leads. | [optional] 
**sort_by** | **str** | The sort method. | [optional] [default to 'DATE_ADDED']
**sort_order** | **str** | The sort order. | [optional] [default to 'DESCENDING']

## Example

```python
from unipile.models.browse_sales_lead_list_request import BrowseSalesLeadListRequest

# TODO update the JSON string below
json = "{}"
# create an instance of BrowseSalesLeadListRequest from a JSON string
browse_sales_lead_list_request_instance = BrowseSalesLeadListRequest.from_json(json)
# print the JSON string representation of the object
print(BrowseSalesLeadListRequest.to_json())

# convert the object into a dict
browse_sales_lead_list_request_dict = browse_sales_lead_list_request_instance.to_dict()
# create an instance of BrowseSalesLeadListRequest from a dict
browse_sales_lead_list_request_from_dict = BrowseSalesLeadListRequest.from_dict(browse_sales_lead_list_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


