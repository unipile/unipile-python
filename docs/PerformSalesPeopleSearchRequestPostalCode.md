# PerformSalesPeopleSearchRequestPostalCode

    Native filter : Personal / Geography / Postal code   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;POSTAL_CODE&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;POSTAL_CODE&#x60; type to find out the possible values. | [optional] 
**radius** | **float** | The distance radius around the postal code in miles. | [optional] 

## Example

```python
from unipile.models.perform_sales_people_search_request_postal_code import PerformSalesPeopleSearchRequestPostalCode

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesPeopleSearchRequestPostalCode from a JSON string
perform_sales_people_search_request_postal_code_instance = PerformSalesPeopleSearchRequestPostalCode.from_json(json)
# print the JSON string representation of the object
print(PerformSalesPeopleSearchRequestPostalCode.to_json())

# convert the object into a dict
perform_sales_people_search_request_postal_code_dict = perform_sales_people_search_request_postal_code_instance.to_dict()
# create an instance of PerformSalesPeopleSearchRequestPostalCode from a dict
perform_sales_people_search_request_postal_code_from_dict = PerformSalesPeopleSearchRequestPostalCode.from_dict(perform_sales_people_search_request_postal_code_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


