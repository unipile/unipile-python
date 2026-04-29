# PerformSalesPeopleSearchRequestLoadRecentSearch

Recent search to be loaded. Overrides all other filters.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;RECENT_SEARCH&#x60; type to find out the possible values.    Native filter : Recent search    | 

## Example

```python
from unipile.models.perform_sales_people_search_request_load_recent_search import PerformSalesPeopleSearchRequestLoadRecentSearch

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesPeopleSearchRequestLoadRecentSearch from a JSON string
perform_sales_people_search_request_load_recent_search_instance = PerformSalesPeopleSearchRequestLoadRecentSearch.from_json(json)
# print the JSON string representation of the object
print(PerformSalesPeopleSearchRequestLoadRecentSearch.to_json())

# convert the object into a dict
perform_sales_people_search_request_load_recent_search_dict = perform_sales_people_search_request_load_recent_search_instance.to_dict()
# create an instance of PerformSalesPeopleSearchRequestLoadRecentSearch from a dict
perform_sales_people_search_request_load_recent_search_from_dict = PerformSalesPeopleSearchRequestLoadRecentSearch.from_dict(perform_sales_people_search_request_load_recent_search_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


