# PeopleSearchResults1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PeopleSearchResults1DataInner]**](PeopleSearchResults1DataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the provider. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.people_search_results1 import PeopleSearchResults1

# TODO update the JSON string below
json = "{}"
# create an instance of PeopleSearchResults1 from a JSON string
people_search_results1_instance = PeopleSearchResults1.from_json(json)
# print the JSON string representation of the object
print(PeopleSearchResults1.to_json())

# convert the object into a dict
people_search_results1_dict = people_search_results1_instance.to_dict()
# create an instance of PeopleSearchResults1 from a dict
people_search_results1_from_dict = PeopleSearchResults1.from_dict(people_search_results1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


