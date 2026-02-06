# PerformSalesPeopleSearchRequestCurrentCompany

    Native filter : Company / Current company   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;COMPANY or ACCOUNT_LIST&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;COMPANY or ACCOUNT_LIST&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.perform_sales_people_search_request_current_company import PerformSalesPeopleSearchRequestCurrentCompany

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesPeopleSearchRequestCurrentCompany from a JSON string
perform_sales_people_search_request_current_company_instance = PerformSalesPeopleSearchRequestCurrentCompany.from_json(json)
# print the JSON string representation of the object
print(PerformSalesPeopleSearchRequestCurrentCompany.to_json())

# convert the object into a dict
perform_sales_people_search_request_current_company_dict = perform_sales_people_search_request_current_company_instance.to_dict()
# create an instance of PerformSalesPeopleSearchRequestCurrentCompany from a dict
perform_sales_people_search_request_current_company_from_dict = PerformSalesPeopleSearchRequestCurrentCompany.from_dict(perform_sales_people_search_request_current_company_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


