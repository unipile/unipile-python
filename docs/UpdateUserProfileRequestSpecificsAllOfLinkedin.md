# UpdateUserProfileRequestSpecificsAllOfLinkedin

Specific options to apply if the provider of the targeted account is Linkedin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**skills** | [**List[UpdateUserProfileRequestSpecificsAllOfLinkedinSkillsInner]**](UpdateUserProfileRequestSpecificsAllOfLinkedinSkillsInner.md) | List of skills to add to the profile. | [optional] 
**skills_follow** | **bool** | Check \&quot;Follow this skill to keep up with relevant content.\&quot; | [optional] [default to False]
**postal_code** | **str** | Postal code associated with the location. | [optional] 
**headline** | **str** | Headline of the profile. | [optional] 
**experience** | [**UpdateUserProfileRequestSpecificsAllOfLinkedinExperience**](UpdateUserProfileRequestSpecificsAllOfLinkedinExperience.md) |  | [optional] 
**education** | [**UpdateUserProfileRequestSpecificsAllOfLinkedinEducation**](UpdateUserProfileRequestSpecificsAllOfLinkedinEducation.md) |  | [optional] 
**picture_options** | [**UpdateUserProfileRequestSpecificsAllOfLinkedinPictureOptions**](UpdateUserProfileRequestSpecificsAllOfLinkedinPictureOptions.md) |  | [optional] 
**background_picture_options** | [**UpdateUserProfileRequestSpecificsAllOfLinkedinPictureOptions**](UpdateUserProfileRequestSpecificsAllOfLinkedinPictureOptions.md) |  | [optional] 
**custom_link** | [**UpdateUserProfileRequestSpecificsAllOfLinkedinCustomLink**](UpdateUserProfileRequestSpecificsAllOfLinkedinCustomLink.md) |  | [optional] 
**open_to_work** | [**UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWork**](UpdateUserProfileRequestSpecificsAllOfLinkedinOpenToWork.md) |  | [optional] 

## Example

```python
from unipile.models.update_user_profile_request_specifics_all_of_linkedin import UpdateUserProfileRequestSpecificsAllOfLinkedin

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedin from a JSON string
update_user_profile_request_specifics_all_of_linkedin_instance = UpdateUserProfileRequestSpecificsAllOfLinkedin.from_json(json)
# print the JSON string representation of the object
print(UpdateUserProfileRequestSpecificsAllOfLinkedin.to_json())

# convert the object into a dict
update_user_profile_request_specifics_all_of_linkedin_dict = update_user_profile_request_specifics_all_of_linkedin_instance.to_dict()
# create an instance of UpdateUserProfileRequestSpecificsAllOfLinkedin from a dict
update_user_profile_request_specifics_all_of_linkedin_from_dict = UpdateUserProfileRequestSpecificsAllOfLinkedin.from_dict(update_user_profile_request_specifics_all_of_linkedin_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


