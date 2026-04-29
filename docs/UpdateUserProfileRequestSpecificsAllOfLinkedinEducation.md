# UpdateUserProfileRequestSpecificsAllOfLinkedinEducation


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**notify_network** | **bool** | Notify the network about the education. Turn on to notify your network of key profile changes (such as new education) and work anniversaries. | [optional] [default to False]
**school** | [**EditExistingEducationSchool**](EditExistingEducationSchool.md) |  | 
**degree** | [**EditExistingEducationDegree**](EditExistingEducationDegree.md) |  | [optional] 
**field_of_study** | [**EditExistingEducationFieldOfStudy**](EditExistingEducationFieldOfStudy.md) |  | [optional] 
**start_date** | [**CreateNewEducationStartDate**](CreateNewEducationStartDate.md) |  | 
**end_date** | [**CreateNewEducationEndDate**](CreateNewEducationEndDate.md) |  | [optional] 
**grade** | **str** | Grade of the education. | [optional] 
**activities** | **str** | Activities and societies. Ex: Alpha Phi Omega, Marching Brand, Volleyball | [optional] 
**description** | **str** | Description of the education. | [optional] 
**skills** | [**List[CreateNewExperienceSkillsInner]**](CreateNewExperienceSkillsInner.md) | List of skills. We recommend adding your top 5 used in this training. They’ll also appear in your profile Skills section. | [optional] 
**media** | [**CreateNewExperienceMedia**](CreateNewExperienceMedia.md) |  | [optional] 
**operation** | **str** |  | 
**id** | **str** | ID of the education to edit. | 

## Example

```python
from unipile.models.update_user_profile_request_specifics_all_of_linkedin_education import UpdateUserProfileRequestSpecificsAllOfLinkedinEducation

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedinEducation from a JSON string
update_user_profile_request_specifics_all_of_linkedin_education_instance = UpdateUserProfileRequestSpecificsAllOfLinkedinEducation.from_json(json)
# print the JSON string representation of the object
print(UpdateUserProfileRequestSpecificsAllOfLinkedinEducation.to_json())

# convert the object into a dict
update_user_profile_request_specifics_all_of_linkedin_education_dict = update_user_profile_request_specifics_all_of_linkedin_education_instance.to_dict()
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedinEducation from a dict
update_user_profile_request_specifics_all_of_linkedin_education_from_dict = UpdateUserProfileRequestSpecificsAllOfLinkedinEducation.from_dict(update_user_profile_request_specifics_all_of_linkedin_education_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


