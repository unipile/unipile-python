# CompaniesSearch1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[CompaniesSearch1DataInner]**](CompaniesSearch1DataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.companies_search1 import CompaniesSearch1

# TODO update the JSON string below
json = "{}"
# create an instance of CompaniesSearch1 from a JSON string
companies_search1_instance = CompaniesSearch1.from_json(json)
# print the JSON string representation of the object
print(CompaniesSearch1.to_json())

# convert the object into a dict
companies_search1_dict = companies_search1_instance.to_dict()
# create an instance of CompaniesSearch1 from a dict
companies_search1_from_dict = CompaniesSearch1.from_dict(companies_search1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


