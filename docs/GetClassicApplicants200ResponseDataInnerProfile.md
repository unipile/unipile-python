# GetClassicApplicants200ResponseDataInnerProfile

The user profile of the Applicant.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the User profile. | 
**display_name** | **str** | The display name of the User profile. | 
**headline** | **str** | The headline of the User profile. | 
**public_identifier** | **str** | The public identifier of the User profile. | [optional] 
**location** | **str** | The location of the User profile. | 
**network_distance** | **str** | Network distance to a User.       &#x60;SELF&#x60;: Yourself.       &#x60;FIRST_DEGREE&#x60;: 1st degree connection.       &#x60;SECOND_DEGREE&#x60;: 2nd degree connection (connection of a 1st degree).       &#x60;THIRD_DEGREE&#x60;: 3rd degree connection (connection of a 2nd degree).       &#x60;OUT_OF_NETWORK&#x60;: Unreachable user.&#39; | 
**profile_url** | **str** | The URL of the User profile. | 
**public_picture_url** | **str** | The picture URL of the User profile. | [optional] 
**work_experience** | [**List[GetClassicApplicants200ResponseDataInnerProfileWorkExperienceInner]**](GetClassicApplicants200ResponseDataInnerProfileWorkExperienceInner.md) | A list of Work experiences. | 
**educations** | [**List[GetClassicApplicants200ResponseDataInnerProfileEducationsInner]**](GetClassicApplicants200ResponseDataInnerProfileEducationsInner.md) | A list of Experiences. | 

## Example

```python
from unipile.models.get_classic_applicants200_response_data_inner_profile import GetClassicApplicants200ResponseDataInnerProfile

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicApplicants200ResponseDataInnerProfile from a JSON string
get_classic_applicants200_response_data_inner_profile_instance = GetClassicApplicants200ResponseDataInnerProfile.from_json(json)
# print the JSON string representation of the object
print(GetClassicApplicants200ResponseDataInnerProfile.to_json())

# convert the object into a dict
get_classic_applicants200_response_data_inner_profile_dict = get_classic_applicants200_response_data_inner_profile_instance.to_dict()
# create an instance of GetClassicApplicants200ResponseDataInnerProfile from a dict
get_classic_applicants200_response_data_inner_profile_from_dict = GetClassicApplicants200ResponseDataInnerProfile.from_dict(get_classic_applicants200_response_data_inner_profile_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


