# PerformRecruiterPeopleSearchFromTalentPoolRequestOccupationInner

Occupations are selections of job titles in the same industry.    Native filter : Occupations   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The occupation name. | 
**id** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;OCCUPATION&#x60; type to find out the possible values. | [optional] 
**priority** | **str** | Whether the user can, must or shouldn&#39;t have the value.    Native filter : Priority    | [optional] [default to 'CAN_HAVE']
**preferences** | **str** | Indicates how this professional experience relates to the user&#39;s current employment status.       | [optional] [default to 'CURRENT_OR_PAST']

## Example

```python
from unipile.models.perform_recruiter_people_search_from_talent_pool_request_occupation_inner import PerformRecruiterPeopleSearchFromTalentPoolRequestOccupationInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestOccupationInner from a JSON string
perform_recruiter_people_search_from_talent_pool_request_occupation_inner_instance = PerformRecruiterPeopleSearchFromTalentPoolRequestOccupationInner.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchFromTalentPoolRequestOccupationInner.to_json())

# convert the object into a dict
perform_recruiter_people_search_from_talent_pool_request_occupation_inner_dict = perform_recruiter_people_search_from_talent_pool_request_occupation_inner_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestOccupationInner from a dict
perform_recruiter_people_search_from_talent_pool_request_occupation_inner_from_dict = PerformRecruiterPeopleSearchFromTalentPoolRequestOccupationInner.from_dict(perform_recruiter_people_search_from_talent_pool_request_occupation_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


