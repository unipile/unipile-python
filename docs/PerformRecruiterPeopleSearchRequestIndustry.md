# PerformRecruiterPeopleSearchRequestIndustry

    Native filter : Industries   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;INDUSTRY&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;INDUSTRY&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.perform_recruiter_people_search_request_industry import PerformRecruiterPeopleSearchRequestIndustry

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchRequestIndustry from a JSON string
perform_recruiter_people_search_request_industry_instance = PerformRecruiterPeopleSearchRequestIndustry.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchRequestIndustry.to_json())

# convert the object into a dict
perform_recruiter_people_search_request_industry_dict = perform_recruiter_people_search_request_industry_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchRequestIndustry from a dict
perform_recruiter_people_search_request_industry_from_dict = PerformRecruiterPeopleSearchRequestIndustry.from_dict(perform_recruiter_people_search_request_industry_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


