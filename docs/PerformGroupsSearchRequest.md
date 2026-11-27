# PerformGroupsSearchRequest

The criteria of the search.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | The keywords used to find social groups. | 
**is_member** | **bool** | Only return the groups the account owner is a member of (if supported by the provider). | [optional] 
**is_public** | **bool** | Only return public social groups (if supported by the provider). | [optional] 

## Example

```python
from unipile.models.perform_groups_search_request import PerformGroupsSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformGroupsSearchRequest from a JSON string
perform_groups_search_request_instance = PerformGroupsSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformGroupsSearchRequest.to_json())

# convert the object into a dict
perform_groups_search_request_dict = perform_groups_search_request_instance.to_dict()
# create an instance of PerformGroupsSearchRequest from a dict
perform_groups_search_request_from_dict = PerformGroupsSearchRequest.from_dict(perform_groups_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


