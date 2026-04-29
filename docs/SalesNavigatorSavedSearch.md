# SalesNavigatorSavedSearch


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**last_viewed_at** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 
**new_results_count** | **float** | The number of comments to the post. &#x60;null&#x60; if counter is hidden. | 

## Example

```python
from unipile.models.sales_navigator_saved_search import SalesNavigatorSavedSearch

# TODO update the JSON string below
json = "{}"
# create an instance of SalesNavigatorSavedSearch from a JSON string
sales_navigator_saved_search_instance = SalesNavigatorSavedSearch.from_json(json)
# print the JSON string representation of the object
print(SalesNavigatorSavedSearch.to_json())

# convert the object into a dict
sales_navigator_saved_search_dict = sales_navigator_saved_search_instance.to_dict()
# create an instance of SalesNavigatorSavedSearch from a dict
sales_navigator_saved_search_from_dict = SalesNavigatorSavedSearch.from_dict(sales_navigator_saved_search_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


