# PagesSearchResults

The pages found, as users of type `organization`.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[GetChatsList200ResponseDataInnerParticipantsInnerUser]**](GetChatsList200ResponseDataInnerParticipantsInnerUser.md) |  | 
**total_count** | **float** | Total number of results if supported by the provider. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.pages_search_results import PagesSearchResults

# TODO update the JSON string below
json = "{}"
# create an instance of PagesSearchResults from a JSON string
pages_search_results_instance = PagesSearchResults.from_json(json)
# print the JSON string representation of the object
print(PagesSearchResults.to_json())

# convert the object into a dict
pages_search_results_dict = pages_search_results_instance.to_dict()
# create an instance of PagesSearchResults from a dict
pages_search_results_from_dict = PagesSearchResults.from_dict(pages_search_results_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


