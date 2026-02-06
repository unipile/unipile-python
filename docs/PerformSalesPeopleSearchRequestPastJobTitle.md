# PerformSalesPeopleSearchRequestPastJobTitle

    Native filter : Role / Past job title   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_TITLE&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-sales-navigator-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_TITLE&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.perform_sales_people_search_request_past_job_title import PerformSalesPeopleSearchRequestPastJobTitle

# TODO update the JSON string below
json = "{}"
# create an instance of PerformSalesPeopleSearchRequestPastJobTitle from a JSON string
perform_sales_people_search_request_past_job_title_instance = PerformSalesPeopleSearchRequestPastJobTitle.from_json(json)
# print the JSON string representation of the object
print(PerformSalesPeopleSearchRequestPastJobTitle.to_json())

# convert the object into a dict
perform_sales_people_search_request_past_job_title_dict = perform_sales_people_search_request_past_job_title_instance.to_dict()
# create an instance of PerformSalesPeopleSearchRequestPastJobTitle from a dict
perform_sales_people_search_request_past_job_title_from_dict = PerformSalesPeopleSearchRequestPastJobTitle.from_dict(perform_sales_people_search_request_past_job_title_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


