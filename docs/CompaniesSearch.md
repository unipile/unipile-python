# CompaniesSearch


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[CompaniesSearchDataInner]**](CompaniesSearchDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.companies_search import CompaniesSearch

# TODO update the JSON string below
json = "{}"
# create an instance of CompaniesSearch from a JSON string
companies_search_instance = CompaniesSearch.from_json(json)
# print the JSON string representation of the object
print(CompaniesSearch.to_json())

# convert the object into a dict
companies_search_dict = companies_search_instance.to_dict()
# create an instance of CompaniesSearch from a dict
companies_search_from_dict = CompaniesSearch.from_dict(companies_search_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


