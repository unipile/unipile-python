# PerformSalesCompaniesSearchRequestDepartmentHeadcountGrowth

    Native filter : Company attributes / Department headcount growth   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**min** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**max** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**department** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_FUNCTION&#x60; type to find out the possible values. | 

## Example

```python
from unipile.models.perform_sales_companies_search_request_department_headcount_growth import PerformSalesCompaniesSearchRequestDepartmentHeadcountGrowth

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesCompaniesSearchRequestDepartmentHeadcountGrowth from a JSON string
perform_sales_companies_search_request_department_headcount_growth_instance = PerformSalesCompaniesSearchRequestDepartmentHeadcountGrowth.from_json(json)
# print the JSON string representation of the object
print(PerformSalesCompaniesSearchRequestDepartmentHeadcountGrowth.to_json())

# convert the object into a dict
perform_sales_companies_search_request_department_headcount_growth_dict = perform_sales_companies_search_request_department_headcount_growth_instance.to_dict()
# create an instance of PerformSalesCompaniesSearchRequestDepartmentHeadcountGrowth from a dict
perform_sales_companies_search_request_department_headcount_growth_from_dict = PerformSalesCompaniesSearchRequestDepartmentHeadcountGrowth.from_dict(perform_sales_companies_search_request_department_headcount_growth_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


