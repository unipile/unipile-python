# BrowseSalesAccountListRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**persona** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;PERSONA&#x60; type to find out the possible values.    Native filter : Persona    | [optional] 
**filter** | **str** |     Native filter : Filter companies    | [optional] 
**sort_by** | **str** | The sort method. | [optional] [default to 'NAME']
**sort_order** | **str** | The sort order. | [optional] [default to 'ASCENDING']

## Example

```python
from unipile.models.browse_sales_account_list_request import BrowseSalesAccountListRequest

# TODO update the JSON string below
json = "{}"
# create an instance of BrowseSalesAccountListRequest from a JSON string
browse_sales_account_list_request_instance = BrowseSalesAccountListRequest.from_json(json)
# print the JSON string representation of the object
print(BrowseSalesAccountListRequest.to_json())

# convert the object into a dict
browse_sales_account_list_request_dict = browse_sales_account_list_request_instance.to_dict()
# create an instance of BrowseSalesAccountListRequest from a dict
browse_sales_account_list_request_from_dict = BrowseSalesAccountListRequest.from_dict(browse_sales_account_list_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


