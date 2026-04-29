# PeopleSearchResults


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PeopleSearchResultsDataInner]**](PeopleSearchResultsDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.people_search_results import PeopleSearchResults

# TODO update the JSON string below
json = "{}"
# create an instance of PeopleSearchResults from a JSON string
people_search_results_instance = PeopleSearchResults.from_json(json)
# print the JSON string representation of the object
print(PeopleSearchResults.to_json())

# convert the object into a dict
people_search_results_dict = people_search_results_instance.to_dict()
# create an instance of PeopleSearchResults from a dict
people_search_results_from_dict = PeopleSearchResults.from_dict(people_search_results_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


