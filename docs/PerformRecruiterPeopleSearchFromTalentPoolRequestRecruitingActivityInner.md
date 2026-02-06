# PerformRecruiterPeopleSearchFromTalentPoolRequestRecruitingActivityInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**priority** | **str** | Whether the user can, must or shouldn&#39;t have the value.    Native filter : Priority    | [optional] [default to 'CAN_HAVE']
**preferences** | **str** | The time period from which to filter results.    Native filter : Preferences    | [optional] [default to 'ANYTIME']

## Example

```python
from unipile.models.perform_recruiter_people_search_from_talent_pool_request_recruiting_activity_inner import PerformRecruiterPeopleSearchFromTalentPoolRequestRecruitingActivityInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestRecruitingActivityInner from a JSON string
perform_recruiter_people_search_from_talent_pool_request_recruiting_activity_inner_instance = PerformRecruiterPeopleSearchFromTalentPoolRequestRecruitingActivityInner.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchFromTalentPoolRequestRecruitingActivityInner.to_json())

# convert the object into a dict
perform_recruiter_people_search_from_talent_pool_request_recruiting_activity_inner_dict = perform_recruiter_people_search_from_talent_pool_request_recruiting_activity_inner_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestRecruitingActivityInner from a dict
perform_recruiter_people_search_from_talent_pool_request_recruiting_activity_inner_from_dict = PerformRecruiterPeopleSearchFromTalentPoolRequestRecruitingActivityInner.from_dict(perform_recruiter_people_search_from_talent_pool_request_recruiting_activity_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


