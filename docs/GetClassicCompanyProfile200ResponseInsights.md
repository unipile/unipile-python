# GetClassicCompanyProfile200ResponseInsights

Insights about the company.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**headcount** | **float** | The number of employees of the Company. | 
**headcount_range** | [**GetClassicCompanyProfile200ResponseInsightsHeadcountRange**](GetClassicCompanyProfile200ResponseInsightsHeadcountRange.md) |  | [optional] 
**heacount_growth** | [**List[GetClassicCompanyProfile200ResponseInsightsHeacountGrowthInner]**](GetClassicCompanyProfile200ResponseInsightsHeacountGrowthInner.md) | A list of time markers to create a chart showing the evolution of the number of employees. | [optional] 
**growth_periods** | [**List[GetClassicCompanyProfile200ResponseInsightsGrowthPeriodsInner]**](GetClassicCompanyProfile200ResponseInsightsGrowthPeriodsInner.md) | A list of time markers to create a chart showing the evolution of the number of employees. | [optional] 
**average_tenure** | **float** | The average years of experience of employees. | [optional] 

## Example

```python
from unipile.models.get_classic_company_profile200_response_insights import GetClassicCompanyProfile200ResponseInsights

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicCompanyProfile200ResponseInsights from a JSON string
get_classic_company_profile200_response_insights_instance = GetClassicCompanyProfile200ResponseInsights.from_json(json)
# print the JSON string representation of the object
print(GetClassicCompanyProfile200ResponseInsights.to_json())

# convert the object into a dict
get_classic_company_profile200_response_insights_dict = get_classic_company_profile200_response_insights_instance.to_dict()
# create an instance of GetClassicCompanyProfile200ResponseInsights from a dict
get_classic_company_profile200_response_insights_from_dict = GetClassicCompanyProfile200ResponseInsights.from_dict(get_classic_company_profile200_response_insights_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


