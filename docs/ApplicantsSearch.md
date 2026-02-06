# ApplicantsSearch


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[ApplicantsSearchDataInner]**](ApplicantsSearchDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.applicants_search import ApplicantsSearch

# TODO update the JSON string below
json = "{}"
# create an instance of ApplicantsSearch from a JSON string
applicants_search_instance = ApplicantsSearch.from_json(json)
# print the JSON string representation of the object
print(ApplicantsSearch.to_json())

# convert the object into a dict
applicants_search_dict = applicants_search_instance.to_dict()
# create an instance of ApplicantsSearch from a dict
applicants_search_from_dict = ApplicantsSearch.from_dict(applicants_search_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


