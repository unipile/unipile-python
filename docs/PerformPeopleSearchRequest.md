# PerformPeopleSearchRequest

The criteria of the search.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | The keywords to search people for. | 
**network_distance** | **List[float]** | Only return the people at these degrees of connection with the account owner (if supported by the provider).   - &#x60;1&#x60; its relations (friends, connections).   - &#x60;2&#x60; the relations of its relations.   - &#x60;3&#x60; the people further away. | [optional] 
**connections_of** | **str** | Only return the relations of this user, given by their ID. | [optional] 
**location** | **List[str]** | Only return the people living in one of these cities. Use the IDs of &#x60;location&#x60; search parameters. | [optional] 
**school** | **List[str]** | Only return the people who went to one of these schools. Use the IDs of &#x60;school&#x60; search parameters. | [optional] 
**company** | **List[str]** | Only return the people who work or worked at one of these companies. Use the IDs of &#x60;company&#x60; search parameters. | [optional] 

## Example

```python
from unipile.models.perform_people_search_request import PerformPeopleSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformPeopleSearchRequest from a JSON string
perform_people_search_request_instance = PerformPeopleSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformPeopleSearchRequest.to_json())

# convert the object into a dict
perform_people_search_request_dict = perform_people_search_request_instance.to_dict()
# create an instance of PerformPeopleSearchRequest from a dict
perform_people_search_request_from_dict = PerformPeopleSearchRequest.from_dict(perform_people_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


