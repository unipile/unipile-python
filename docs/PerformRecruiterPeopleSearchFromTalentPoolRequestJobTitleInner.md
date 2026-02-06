# PerformRecruiterPeopleSearchFromTalentPoolRequestJobTitleInner

    Native filter : Job titles   

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The job title. | 
**id** | **str** |  | [optional] 
**priority** | **str** | Whether the user can, must or shouldn&#39;t have the value.    Native filter : Priority    | [optional] [default to 'CAN_HAVE']
**preferences** | **str** | Indicates how this professional experience relates to the user&#39;s current employment status.       | [optional] [default to 'CURRENT_OR_PAST']

## Example

```python
from unipile.models.perform_recruiter_people_search_from_talent_pool_request_job_title_inner import PerformRecruiterPeopleSearchFromTalentPoolRequestJobTitleInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestJobTitleInner from a JSON string
perform_recruiter_people_search_from_talent_pool_request_job_title_inner_instance = PerformRecruiterPeopleSearchFromTalentPoolRequestJobTitleInner.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchFromTalentPoolRequestJobTitleInner.to_json())

# convert the object into a dict
perform_recruiter_people_search_from_talent_pool_request_job_title_inner_dict = perform_recruiter_people_search_from_talent_pool_request_job_title_inner_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestJobTitleInner from a dict
perform_recruiter_people_search_from_talent_pool_request_job_title_inner_from_dict = PerformRecruiterPeopleSearchFromTalentPoolRequestJobTitleInner.from_dict(perform_recruiter_people_search_from_talent_pool_request_job_title_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


