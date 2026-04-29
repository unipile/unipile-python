# PerformSalesPeopleSearchRequestGroup

    Native filter : Personal / Groups   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;GROUP&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;GROUP&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.perform_sales_people_search_request_group import PerformSalesPeopleSearchRequestGroup

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesPeopleSearchRequestGroup from a JSON string
perform_sales_people_search_request_group_instance = PerformSalesPeopleSearchRequestGroup.from_json(json)
# print the JSON string representation of the object
print(PerformSalesPeopleSearchRequestGroup.to_json())

# convert the object into a dict
perform_sales_people_search_request_group_dict = perform_sales_people_search_request_group_instance.to_dict()
# create an instance of PerformSalesPeopleSearchRequestGroup from a dict
perform_sales_people_search_request_group_from_dict = PerformSalesPeopleSearchRequestGroup.from_dict(perform_sales_people_search_request_group_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


