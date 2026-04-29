# PerformRecruiterPeopleSearchFromTalentPoolRequestLoadCustomFilter

Custom filter to be loaded. Can be associated with other filters.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;CUSTOM_FILTER&#x60; type to find out the possible values.    Native filter : Custom filters    | 

## Example

```python
from unipile.models.perform_recruiter_people_search_from_talent_pool_request_load_custom_filter import PerformRecruiterPeopleSearchFromTalentPoolRequestLoadCustomFilter

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestLoadCustomFilter from a JSON string
perform_recruiter_people_search_from_talent_pool_request_load_custom_filter_instance = PerformRecruiterPeopleSearchFromTalentPoolRequestLoadCustomFilter.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchFromTalentPoolRequestLoadCustomFilter.to_json())

# convert the object into a dict
perform_recruiter_people_search_from_talent_pool_request_load_custom_filter_dict = perform_recruiter_people_search_from_talent_pool_request_load_custom_filter_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestLoadCustomFilter from a dict
perform_recruiter_people_search_from_talent_pool_request_load_custom_filter_from_dict = PerformRecruiterPeopleSearchFromTalentPoolRequestLoadCustomFilter.from_dict(perform_recruiter_people_search_from_talent_pool_request_load_custom_filter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


