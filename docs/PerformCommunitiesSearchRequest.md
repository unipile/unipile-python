# PerformCommunitiesSearchRequest

The criteria of the search.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | The keywords to search communities for. | 

## Example

```python
from unipile.models.perform_communities_search_request import PerformCommunitiesSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformCommunitiesSearchRequest from a JSON string
perform_communities_search_request_instance = PerformCommunitiesSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformCommunitiesSearchRequest.to_json())

# convert the object into a dict
perform_communities_search_request_dict = perform_communities_search_request_instance.to_dict()
# create an instance of PerformCommunitiesSearchRequest from a dict
perform_communities_search_request_from_dict = PerformCommunitiesSearchRequest.from_dict(perform_communities_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


