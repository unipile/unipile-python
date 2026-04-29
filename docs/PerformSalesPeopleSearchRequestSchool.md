# PerformSalesPeopleSearchRequestSchool

    Native filter : Personal / School   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SCHOOL&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SCHOOL&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.perform_sales_people_search_request_school import PerformSalesPeopleSearchRequestSchool

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesPeopleSearchRequestSchool from a JSON string
perform_sales_people_search_request_school_instance = PerformSalesPeopleSearchRequestSchool.from_json(json)
# print the JSON string representation of the object
print(PerformSalesPeopleSearchRequestSchool.to_json())

# convert the object into a dict
perform_sales_people_search_request_school_dict = perform_sales_people_search_request_school_instance.to_dict()
# create an instance of PerformSalesPeopleSearchRequestSchool from a dict
perform_sales_people_search_request_school_from_dict = PerformSalesPeopleSearchRequestSchool.from_dict(perform_sales_people_search_request_school_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


