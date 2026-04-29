# PerformRecruiterPeopleSearchFromTalentPoolRequestSpokenLanguageInner

    Native filter : Spoken languages   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SPOKEN_LANGUAGE&#x60; type to find out the possible values. | 
**priority** | **str** | Whether the user can, must or shouldn&#39;t have the value.    Native filter : Priority    | [optional] [default to 'CAN_HAVE']
**proficiency** | **str** | The level of proficiency for the spoken languages.    Native filter : Spoken languages proficiency    | [optional] 

## Example

```python
from unipile.models.perform_recruiter_people_search_from_talent_pool_request_spoken_language_inner import PerformRecruiterPeopleSearchFromTalentPoolRequestSpokenLanguageInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestSpokenLanguageInner from a JSON string
perform_recruiter_people_search_from_talent_pool_request_spoken_language_inner_instance = PerformRecruiterPeopleSearchFromTalentPoolRequestSpokenLanguageInner.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchFromTalentPoolRequestSpokenLanguageInner.to_json())

# convert the object into a dict
perform_recruiter_people_search_from_talent_pool_request_spoken_language_inner_dict = perform_recruiter_people_search_from_talent_pool_request_spoken_language_inner_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestSpokenLanguageInner from a dict
perform_recruiter_people_search_from_talent_pool_request_spoken_language_inner_from_dict = PerformRecruiterPeopleSearchFromTalentPoolRequestSpokenLanguageInner.from_dict(perform_recruiter_people_search_from_talent_pool_request_spoken_language_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


