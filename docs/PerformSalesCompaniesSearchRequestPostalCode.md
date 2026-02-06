# PerformSalesCompaniesSearchRequestPostalCode

    Native filter : Company attributes / Headquarters location / Postal code   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;POSTAL_CODE&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;POSTAL_CODE&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.perform_sales_companies_search_request_postal_code import PerformSalesCompaniesSearchRequestPostalCode

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesCompaniesSearchRequestPostalCode from a JSON string
perform_sales_companies_search_request_postal_code_instance = PerformSalesCompaniesSearchRequestPostalCode.from_json(json)
# print the JSON string representation of the object
print(PerformSalesCompaniesSearchRequestPostalCode.to_json())

# convert the object into a dict
perform_sales_companies_search_request_postal_code_dict = perform_sales_companies_search_request_postal_code_instance.to_dict()
# create an instance of PerformSalesCompaniesSearchRequestPostalCode from a dict
perform_sales_companies_search_request_postal_code_from_dict = PerformSalesCompaniesSearchRequestPostalCode.from_dict(perform_sales_companies_search_request_postal_code_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


