# ApplicantsSearchDataInnerProfile


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the user. | 
**headline** | **str** | The headline of the User. | 
**network_distance** | **str** | Network distance to a User.       &#x60;SELF&#x60;: Yourself.       &#x60;FIRST_DEGREE&#x60;: 1st degree connection.       &#x60;SECOND_DEGREE&#x60;: 2nd degree connection (connection of a 1st degree).       &#x60;THIRD_DEGREE&#x60;: 3rd degree connection (connection of a 2nd degree).       &#x60;OUT_OF_NETWORK&#x60;: Unreachable user.&#39; | 
**location** | **str** | The location of the User. | 
**can_send_inmail** | **bool** | Whether it is possible to send an inMail to this User. | [optional] 
**visibility** | **str** | Indidates that you have access to the full profile of this User. | 
**candidate_id** | **str** | The candidate ID of the User. | 
**is_hidden_candidate** | **bool** | Whether the User has been set as hidden candidate. | 
**hiring_project** | [**PartialProfileHiringProject**](PartialProfileHiringProject.md) |  | [optional] 
**work_experience** | [**List[PartialProfileWorkExperienceInner]**](PartialProfileWorkExperienceInner.md) | A list of the User&#39;s work experiences. | 
**member_id** | **str** | The LinkedIn internal member ID of the user. | [optional] 
**display_name** | **str** | The display name of the User. | 
**public_identifier** | **str** | The public identifier of the User. | [optional] 
**profile_url** | **str** | The profile URL of the User. | [optional] 
**public_picture_url** | **str** | The public picture URL of the User. | [optional] 
**public_picture_url_large** | **str** | The public picture URL of the User in large size. | [optional] 
**relations_count** | **float** | The number of relations of the User. | [optional] 
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
from unipile.models.applicants_search_data_inner_profile import ApplicantsSearchDataInnerProfile

# TODO update the JSON string below
json = "{}"
# create an instance of ApplicantsSearchDataInnerProfile from a JSON string
applicants_search_data_inner_profile_instance = ApplicantsSearchDataInnerProfile.from_json(json)
# print the JSON string representation of the object
print(ApplicantsSearchDataInnerProfile.to_json())

# convert the object into a dict
applicants_search_data_inner_profile_dict = applicants_search_data_inner_profile_instance.to_dict()
# create an instance of ApplicantsSearchDataInnerProfile from a dict
applicants_search_data_inner_profile_from_dict = ApplicantsSearchDataInnerProfile.from_dict(applicants_search_data_inner_profile_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


