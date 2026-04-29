# PerformSalesPeopleSearchRequestAccountList

    Native filter : Workflow / Account lists   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;ACCOUNT_LIST&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;ACCOUNT_LIST&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.perform_sales_people_search_request_account_list import PerformSalesPeopleSearchRequestAccountList

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesPeopleSearchRequestAccountList from a JSON string
perform_sales_people_search_request_account_list_instance = PerformSalesPeopleSearchRequestAccountList.from_json(json)
# print the JSON string representation of the object
print(PerformSalesPeopleSearchRequestAccountList.to_json())

# convert the object into a dict
perform_sales_people_search_request_account_list_dict = perform_sales_people_search_request_account_list_instance.to_dict()
# create an instance of PerformSalesPeopleSearchRequestAccountList from a dict
perform_sales_people_search_request_account_list_from_dict = PerformSalesPeopleSearchRequestAccountList.from_dict(perform_sales_people_search_request_account_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


