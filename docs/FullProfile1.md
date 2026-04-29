# FullProfile1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the user. | 
**member_id** | **str** | The LinkedIn internal member ID of the user. | [optional] 
**display_name** | **str** | The display name of the User. | 
**public_identifier** | **str** | The public identifier of the User. | [optional] 
**profile_url** | **str** | The profile URL of the User. | [optional] 
**public_picture_url** | **str** | The public picture URL of the User. | [optional] 
**public_picture_url_large** | **str** | The public picture URL of the User in large size. | [optional] 
**relations_count** | **float** | The number of relations of the User. | [optional] 
**location** | **str** | The location of the User. | 
**headline** | **str** | The headline of the User. | 
**network_distance** | **str** | Network distance to a User.       &#x60;SELF&#x60;: Yourself.       &#x60;FIRST_DEGREE&#x60;: 1st degree connection.       &#x60;SECOND_DEGREE&#x60;: 2nd degree connection (connection of a 1st degree).       &#x60;THIRD_DEGREE&#x60;: 3rd degree connection (connection of a 2nd degree).       &#x60;OUT_OF_NETWORK&#x60;: Unreachable user.&#39; | 
**can_send_inmail** | **bool** | Whether it is possible to send an inMail to this User. | [optional] 
**product** | **str** |  | 
**visibility** | **str** | Indidates that you have access to the full profile of this User. | 
**candidate_id** | **str** | The candidate ID of the User. | 
**is_hidden_candidate** | **bool** | Whether the User has been set as hidden candidate. | 
**hiring_project** | [**PartialProfileHiringProject**](PartialProfileHiringProject.md) |  | [optional] 
**work_experience** | [**List[PartialProfileWorkExperienceInner]**](PartialProfileWorkExperienceInner.md) | A list of the User&#39;s work experiences. | 
**industry** | **str** | The industry to which the User belongs. | 
**followers_count** | **float** | The number of the followers of the User. | [optional] 
**skills** | [**List[FullProfileSkillsInner]**](FullProfileSkillsInner.md) | A list of skills. | 
**summary** | **str** | The summary of the User. | [optional] 
**emails** | **List[str]** |  | [optional] 
**phone_numbers** | **List[str]** |  | [optional] 
**education** | [**List[FullProfileEducationInner]**](FullProfileEducationInner.md) |  | 
**languages** | [**List[LinkedInLanguagesInner]**](LinkedInLanguagesInner.md) |  | 
**certifications** | [**List[FullProfileCertificationsInner]**](FullProfileCertificationsInner.md) |  | 
**projects** | [**List[FullProfileProjectsInner]**](FullProfileProjectsInner.md) |  | 
**volunteering** | [**List[LinkedInVolunteerExperienceInner]**](LinkedInVolunteerExperienceInner.md) |  | 
**recommendations** | [**List[LinkedInRecommendationsReceivedInner]**](LinkedInRecommendationsReceivedInner.md) |  | 

## Example

```python
from unipile.models.full_profile1 import FullProfile1

# TODO update the JSON string below
json = "{}"
# create an instance of FullProfile1 from a JSON string
full_profile1_instance = FullProfile1.from_json(json)
# print the JSON string representation of the object
print(FullProfile1.to_json())

# convert the object into a dict
full_profile1_dict = full_profile1_instance.to_dict()
# create an instance of FullProfile1 from a dict
full_profile1_from_dict = FullProfile1.from_dict(full_profile1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


