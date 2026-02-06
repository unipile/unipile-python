# PerformClassicCompaniesSearchRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | A keyword or group of keywords. | [optional] 
**location** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;LOCATION&#x60; type to find out the possible values.    Native filter : Locations    | [optional] 
**industry** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;INDUSTRY&#x60; type to find out the possible values.    Native filter : Industry    | [optional] 
**headcount** | [**List[PerformClassicCompaniesSearchRequestHeadcountInner]**](PerformClassicCompaniesSearchRequestHeadcountInner.md) |  | [optional] 
**has_job_postings** | **bool** | Whether the companies should have active job postings on LinkedIn.    Native filter : Job listings on LinkedIn    | [optional] 
**is_employing_relations** | **bool** | Whether the companies should have first degree relations among employees.    Native filter : Relations    | [optional] 

## Example

```python
from unipile.models.perform_classic_companies_search_request import PerformClassicCompaniesSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicCompaniesSearchRequest from a JSON string
perform_classic_companies_search_request_instance = PerformClassicCompaniesSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformClassicCompaniesSearchRequest.to_json())

# convert the object into a dict
perform_classic_companies_search_request_dict = perform_classic_companies_search_request_instance.to_dict()
# create an instance of PerformClassicCompaniesSearchRequest from a dict
perform_classic_companies_search_request_from_dict = PerformClassicCompaniesSearchRequest.from_dict(perform_classic_companies_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


