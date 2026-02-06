# PerformSalesCompaniesSearchRequestLocation

    Native filter : Company attributes / Headquarters location / Region   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;LOCATION&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;LOCATION&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.perform_sales_companies_search_request_location import PerformSalesCompaniesSearchRequestLocation

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesCompaniesSearchRequestLocation from a JSON string
perform_sales_companies_search_request_location_instance = PerformSalesCompaniesSearchRequestLocation.from_json(json)
# print the JSON string representation of the object
print(PerformSalesCompaniesSearchRequestLocation.to_json())

# convert the object into a dict
perform_sales_companies_search_request_location_dict = perform_sales_companies_search_request_location_instance.to_dict()
# create an instance of PerformSalesCompaniesSearchRequestLocation from a dict
perform_sales_companies_search_request_location_from_dict = PerformSalesCompaniesSearchRequestLocation.from_dict(perform_sales_companies_search_request_location_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


