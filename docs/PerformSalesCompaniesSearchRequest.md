# PerformSalesCompaniesSearchRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | A keyword or group of keywords. | [optional] 
**save_search** | [**PerformSalesPeopleSearchRequestSaveSearch**](PerformSalesPeopleSearchRequestSaveSearch.md) |  | [optional] 
**load_saved_search** | [**PerformSalesPeopleSearchRequestLoadSavedSearch**](PerformSalesPeopleSearchRequestLoadSavedSearch.md) |  | [optional] 
**load_recent_search** | [**PerformSalesPeopleSearchRequestLoadRecentSearch**](PerformSalesPeopleSearchRequestLoadRecentSearch.md) |  | [optional] 
**annual_revenue** | [**PerformSalesCompaniesSearchRequestAnnualRevenue**](PerformSalesCompaniesSearchRequestAnnualRevenue.md) |  | [optional] 
**headcount** | [**List[PerformSalesCompaniesSearchRequestHeadcountInner]**](PerformSalesCompaniesSearchRequestHeadcountInner.md) | A list of headcount ranges. | [optional] 
**headcount_growth** | [**PerformSalesCompaniesSearchRequestHeadcountGrowth**](PerformSalesCompaniesSearchRequestHeadcountGrowth.md) |  | [optional] 
**location** | [**PerformSalesCompaniesSearchRequestLocation**](PerformSalesCompaniesSearchRequestLocation.md) |  | [optional] 
**postal_code** | [**PerformSalesCompaniesSearchRequestPostalCode**](PerformSalesCompaniesSearchRequestPostalCode.md) |  | [optional] 
**industry** | [**PerformSalesCompaniesSearchRequestIndustry**](PerformSalesCompaniesSearchRequestIndustry.md) |  | [optional] 
**followers** | [**List[PerformSalesCompaniesSearchRequestFollowersInner]**](PerformSalesCompaniesSearchRequestFollowersInner.md) | A list of followers ranges. | [optional] 
**department_headcount** | [**PerformSalesCompaniesSearchRequestDepartmentHeadcount**](PerformSalesCompaniesSearchRequestDepartmentHeadcount.md) |  | [optional] 
**department_headcount_growth** | [**PerformSalesCompaniesSearchRequestDepartmentHeadcountGrowth**](PerformSalesCompaniesSearchRequestDepartmentHeadcountGrowth.md) |  | [optional] 
**fortune** | [**List[PerformSalesCompaniesSearchRequestFortuneInner]**](PerformSalesCompaniesSearchRequestFortuneInner.md) | A list of fortune ranges. | [optional] 
**spotlights** | **List[str]** | A list of spotlights. | [optional] 
**saved_accounts** | **bool** | Whether to include all your saved accounts in the results.    Native filter : Workflow / Saved accounts / All my saved accounts    | [optional] 
**account_list** | [**PerformSalesCompaniesSearchRequestAccountList**](PerformSalesCompaniesSearchRequestAccountList.md) |  | [optional] 

## Example

```python
from unipile.models.perform_sales_companies_search_request import PerformSalesCompaniesSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesCompaniesSearchRequest from a JSON string
perform_sales_companies_search_request_instance = PerformSalesCompaniesSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformSalesCompaniesSearchRequest.to_json())

# convert the object into a dict
perform_sales_companies_search_request_dict = perform_sales_companies_search_request_instance.to_dict()
# create an instance of PerformSalesCompaniesSearchRequest from a dict
perform_sales_companies_search_request_from_dict = PerformSalesCompaniesSearchRequest.from_dict(perform_sales_companies_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


