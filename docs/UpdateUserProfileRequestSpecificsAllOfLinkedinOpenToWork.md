# UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWork


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_title** | [**List[UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWorkJobTitleInner]**](UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWorkJobTitleInner.md) | A list of job titles you would like to hold. | 
**workplace** | [**List[UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWorkWorkplaceInner]**](UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWorkWorkplaceInner.md) | A list of desired workplaces. | 
**start_date** | **str** | The timeframe by which you would like to start. | [optional] 
**employment_type** | **List[str]** | A list of employment types. | [optional] 
**visibility** | **str** | Who can view that you are open to work. | 

## Example

```python
from unipile.models.update_user_profile_request_specifics_all_of_linkedin_open_to_work import UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWork

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWork from a JSON string
update_user_profile_request_specifics_all_of_linkedin_open_to_work_instance = UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWork.from_json(json)
# print the JSON string representation of the object
print(UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWork.to_json())

# convert the object into a dict
update_user_profile_request_specifics_all_of_linkedin_open_to_work_dict = update_user_profile_request_specifics_all_of_linkedin_open_to_work_instance.to_dict()
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWork from a dict
update_user_profile_request_specifics_all_of_linkedin_open_to_work_from_dict = UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWork.from_dict(update_user_profile_request_specifics_all_of_linkedin_open_to_work_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


