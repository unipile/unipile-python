# PerformSalesPeopleSearchRequestLoadSavedSearch

Saved search to be loaded. Overrides all other filters.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SAVED_PEOPLE_SEARCH&#x60; type to find out the possible values.    Native filter : Saved search    | 
**last_viewed_at** | **float** | A Unix timestamp indicating the last time the search results were accessed, to be used to retrieve only the new results. | [optional] 

## Example

```python
from unipile.models.perform_sales_people_search_request_load_saved_search import PerformSalesPeopleSearchRequestLoadSavedSearch

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesPeopleSearchRequestLoadSavedSearch from a JSON string
perform_sales_people_search_request_load_saved_search_instance = PerformSalesPeopleSearchRequestLoadSavedSearch.from_json(json)
# print the JSON string representation of the object
print(PerformSalesPeopleSearchRequestLoadSavedSearch.to_json())

# convert the object into a dict
perform_sales_people_search_request_load_saved_search_dict = perform_sales_people_search_request_load_saved_search_instance.to_dict()
# create an instance of PerformSalesPeopleSearchRequestLoadSavedSearch from a dict
perform_sales_people_search_request_load_saved_search_from_dict = PerformSalesPeopleSearchRequestLoadSavedSearch.from_dict(perform_sales_people_search_request_load_saved_search_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


