# PerformRecruiterPeopleSearchFromTalentPoolRequestLocationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | 
**priority** | **str** | Whether the user can, must or shouldn&#39;t have the value.    Native filter : Priority    | [optional] [default to 'CAN_HAVE']
**preferences** | **str** | Indicates the location preference of the user.       | [optional] [default to 'CURRENT']

## Example

```python
from unipile.models.perform_recruiter_people_search_from_talent_pool_request_location_inner import PerformRecruiterPeopleSearchFromTalentPoolRequestLocationInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestLocationInner from a JSON string
perform_recruiter_people_search_from_talent_pool_request_location_inner_instance = PerformRecruiterPeopleSearchFromTalentPoolRequestLocationInner.from_json(json)
# print the JSON string representation of the object
print(PerformRecruiterPeopleSearchFromTalentPoolRequestLocationInner.to_json())

# convert the object into a dict
perform_recruiter_people_search_from_talent_pool_request_location_inner_dict = perform_recruiter_people_search_from_talent_pool_request_location_inner_instance.to_dict()
# create an instance of PerformRecruiterPeopleSearchFromTalentPoolRequestLocationInner from a dict
perform_recruiter_people_search_from_talent_pool_request_location_inner_from_dict = PerformRecruiterPeopleSearchFromTalentPoolRequestLocationInner.from_dict(perform_recruiter_people_search_from_talent_pool_request_location_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


