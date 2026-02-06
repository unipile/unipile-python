# GetUserProfile200ResponseSpecificsAllOfAnyOfVolunteerExperienceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organization** | [**GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInnerOrganization**](GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInnerOrganization.md) |  | [optional] 
**role** | **str** | Role in the experience. | 
**cause** | **str** | Cause of the experience. | [optional] 
**description** | **str** | Description of the experience. | [optional] 
**started_on** | **str** | Start date of the experience in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | End date of the experience in MM/DD/YYYY format. | [optional] 

## Example

```python
from unipile.models.get_user_profile200_response_specifics_all_of_any_of_volunteer_experience_inner import GetUserProfile200ResponseSpecificsAllOfAnyOfVolunteerExperienceInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfVolunteerExperienceInner from a JSON string
get_user_profile200_response_specifics_all_of_any_of_volunteer_experience_inner_instance = GetUserProfile200ResponseSpecificsAllOfAnyOfVolunteerExperienceInner.from_json(json)
# print the JSON string representation of the object
print(GetUserProfile200ResponseSpecificsAllOfAnyOfVolunteerExperienceInner.to_json())

# convert the object into a dict
get_user_profile200_response_specifics_all_of_any_of_volunteer_experience_inner_dict = get_user_profile200_response_specifics_all_of_any_of_volunteer_experience_inner_instance.to_dict()
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfVolunteerExperienceInner from a dict
get_user_profile200_response_specifics_all_of_any_of_volunteer_experience_inner_from_dict = GetUserProfile200ResponseSpecificsAllOfAnyOfVolunteerExperienceInner.from_dict(get_user_profile200_response_specifics_all_of_any_of_volunteer_experience_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


