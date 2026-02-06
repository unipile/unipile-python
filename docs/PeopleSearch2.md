# PeopleSearch2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[PeopleSearch2DataInner]**](PeopleSearch2DataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.people_search2 import PeopleSearch2

# TODO update the JSON string below
json = "{}"
# create an instance of PeopleSearch2 from a JSON string
people_search2_instance = PeopleSearch2.from_json(json)
# print the JSON string representation of the object
print(PeopleSearch2.to_json())

# convert the object into a dict
people_search2_dict = people_search2_instance.to_dict()
# create an instance of PeopleSearch2 from a dict
people_search2_from_dict = PeopleSearch2.from_dict(people_search2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


