# PerformRecruiterPeopleSearchFromTalentPoolRequestLoadSavedSearch

Saved search to be loaded. Can be associated with other filters.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SAVED_SEARCH&#x60; type to find out the possible values.    Native filter : Saved searches    | 
**new_results_only** | **bool** | Whether only newest results should be returned. | [optional] 

## Example

```python
from unipile.models.perform_recruiter_people_search_from_talent_pool_request_load_saved_search import PerformRecruiterPeopleSearchFromTalentPoolRequestLoadSavedSearch

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestLoadSavedSearch from a JSON string
perform_recruiter_people_search_from_talent_pool_request_load_saved_search_instance = PerformRecruiterPeopleSearchFromTalentPoolRequestLoadSavedSearch.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchFromTalentPoolRequestLoadSavedSearch.to_json())

# convert the object into a dict
perform_recruiter_people_search_from_talent_pool_request_load_saved_search_dict = perform_recruiter_people_search_from_talent_pool_request_load_saved_search_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestLoadSavedSearch from a dict
perform_recruiter_people_search_from_talent_pool_request_load_saved_search_from_dict = PerformRecruiterPeopleSearchFromTalentPoolRequestLoadSavedSearch.from_dict(perform_recruiter_people_search_from_talent_pool_request_load_saved_search_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


