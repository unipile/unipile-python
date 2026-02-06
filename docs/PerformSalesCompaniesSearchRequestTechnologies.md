# PerformSalesCompaniesSearchRequestTechnologies

    Native filter : Company attributes / Technologies used   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;TECHNOLOGY&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;TECHNOLOGY&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.perform_sales_companies_search_request_technologies import PerformSalesCompaniesSearchRequestTechnologies

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesCompaniesSearchRequestTechnologies from a JSON string
perform_sales_companies_search_request_technologies_instance = PerformSalesCompaniesSearchRequestTechnologies.from_json(json)
# print the JSON string representation of the object
print(PerformSalesCompaniesSearchRequestTechnologies.to_json())

# convert the object into a dict
perform_sales_companies_search_request_technologies_dict = perform_sales_companies_search_request_technologies_instance.to_dict()
# create an instance of PerformSalesCompaniesSearchRequestTechnologies from a dict
perform_sales_companies_search_request_technologies_from_dict = PerformSalesCompaniesSearchRequestTechnologies.from_dict(perform_sales_companies_search_request_technologies_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


