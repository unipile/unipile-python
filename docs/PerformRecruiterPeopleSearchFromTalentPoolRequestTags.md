# PerformRecruiterPeopleSearchFromTalentPoolRequestTags

    Native filter : Tags   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**include** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;TAG&#x60; type to find out the possible values. | [optional] 
**exclude** | **List[str]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;TAG&#x60; type to find out the possible values. | [optional] 

## Example

```python
from unipile.models.perform_recruiter_people_search_from_talent_pool_request_tags import PerformRecruiterPeopleSearchFromTalentPoolRequestTags

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestTags from a JSON string
perform_recruiter_people_search_from_talent_pool_request_tags_instance = PerformRecruiterPeopleSearchFromTalentPoolRequestTags.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchFromTalentPoolRequestTags.to_json())

# convert the object into a dict
perform_recruiter_people_search_from_talent_pool_request_tags_dict = perform_recruiter_people_search_from_talent_pool_request_tags_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestTags from a dict
perform_recruiter_people_search_from_talent_pool_request_tags_from_dict = PerformRecruiterPeopleSearchFromTalentPoolRequestTags.from_dict(perform_recruiter_people_search_from_talent_pool_request_tags_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


