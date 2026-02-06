# PerformClassicJobsSearchRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | A keyword or group of keywords. | [optional] 
**sort_by** | **str** | The sort method.    Native filter : Sort by    | [optional] 
**date_posted** | **str** | The time period when the jobs should have been published.    Native filter : Date posted    | [optional] 
**workplace_type** | **List[str]** |  | [optional] 
**seniority** | **List[str]** |  | [optional] 
**employment_status** | **List[str]** |  | [optional] 
**company** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;COMPANY&#x60; type to find out the possible values.    Native filter : Company    | [optional] 
**primary_location** | **str** |  | [optional] 
**location** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;LOCATION&#x60; type to find out the possible values.    Native filter : Location    | [optional] 
**location_radius** | **float** | The distance radius around the location in kilometers.    Native filter : Distance    | [optional] 
**industry** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;INDUSTRY&#x60; type to find out the possible values.    Native filter : Industry    | [optional] 
**function** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_FUNCTION&#x60; type to find out the possible values.    Native filter : Job function    | [optional] 
**job_title** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;JOB_TITLE&#x60; type to find out the possible values.    Native filter : Job title    | [optional] 
**easy_apply** | **bool** | Whether the application can me made directly on LinkedIn.    Native filter : Easy apply    | [optional] 
**has_verifications** | **bool** | Whether the jobs have a verification badge.    Native filter : Has verifications    | [optional] 
**under_10_applicants** | **bool** | Whether the jobs didn&#39;t receive more than 10 applications.    Native filter : Under 10 applicants    | [optional] 
**in_your_network** | **bool** | Whether the jobs have been published by relations of you.    Native filter : In your network    | [optional] 
**fair_chance_employer** | **bool** | Whether the jobs accept applicants with criminal records.    Native filter : Fair chance employer    | [optional] 
**salary** | [**PerformClassicJobsSearchRequestSalary**](PerformClassicJobsSearchRequestSalary.md) |  | [optional] 
**benefits** | **List[str]** | A list of benefits. | [optional] 
**commitments** | **List[str]** | A list of commitments. | [optional] 

## Example

```python
from unipile.models.perform_classic_jobs_search_request import PerformClassicJobsSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicJobsSearchRequest from a JSON string
perform_classic_jobs_search_request_instance = PerformClassicJobsSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformClassicJobsSearchRequest.to_json())

# convert the object into a dict
perform_classic_jobs_search_request_dict = perform_classic_jobs_search_request_instance.to_dict()
# create an instance of PerformClassicJobsSearchRequest from a dict
perform_classic_jobs_search_request_from_dict = PerformClassicJobsSearchRequest.from_dict(perform_classic_jobs_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


