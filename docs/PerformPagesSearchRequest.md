# PerformPagesSearchRequest

The criteria of the search.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | The keywords to search pages for. | 
**location** | **List[str]** | Only return the pages located in one of these cities. Use the IDs of &#x60;location&#x60; search parameters. | [optional] 

## Example

```python
from unipile.models.perform_pages_search_request import PerformPagesSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformPagesSearchRequest from a JSON string
perform_pages_search_request_instance = PerformPagesSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformPagesSearchRequest.to_json())

# convert the object into a dict
perform_pages_search_request_dict = perform_pages_search_request_instance.to_dict()
# create an instance of PerformPagesSearchRequest from a dict
perform_pages_search_request_from_dict = PerformPagesSearchRequest.from_dict(perform_pages_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


