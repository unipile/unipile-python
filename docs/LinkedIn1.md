# LinkedIn1

LinkedIn specific dataset for user profiles.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**member_id** | **str** | LinkedIn internal member ID of the user. | [optional] 
**industry** | **str** | The industry of the user&#39;s current company. | [optional] 
**can_send_inmail** | **bool** | Whether the user can be reached with inmails. | [optional] 
**network_distance** | **str** | Network distance to a User.       &#x60;SELF&#x60;: Yourself.       &#x60;FIRST_DEGREE&#x60;: 1st degree connection.       &#x60;SECOND_DEGREE&#x60;: 2nd degree connection (connection of a 1st degree).       &#x60;THIRD_DEGREE&#x60;: 3rd degree connection (connection of a 2nd degree).       &#x60;OUT_OF_NETWORK&#x60;: Unreachable user.&#39; | 
**relation_request** | [**LinkedIn1RelationRequest**](LinkedIn1RelationRequest.md) |  | [optional] 
**relation_request_status** | **str** | The status of the relation request with the user if any. | [optional] 
**pronoun** | **str** | The pronoun to be used to refer to this user. | [optional] 
**default_locale** | **str** | Default locale for the user&#39;s profile (POSIX format e.g. en_US, fr_FR...). | [optional] 
**supported_locales** | **List[Optional[str]]** | List of supported locales for the user&#39;s profile (POSIX format e.g. en_US, fr_FR...). | [optional] 
**notify_visit_token** | **str** | Payload that should be passed to the Notify profile visit route in order to notify the visit. | [optional] 
**is_open_profile** | **bool** | Whether the user has an open profile (can be reached with free inmails). | [optional] 
**is_premium** | **bool** | Whether the user has a premium subscription. | [optional] 
**is_influencer** | **bool** | Whether the user is an influencer. | [optional] 
**is_creator** | **bool** | Whether the user is a creator. | [optional] 
**is_hiring** | **bool** | Whether the user is hiring. | [optional] 
**is_open_to_work** | **bool** | Whether the user is open to work. | [optional] 
**is_saved_lead** | **bool** | Whether the user is a saved lead. | [optional] 
**is_crm_imported** | **bool** | Whether the user is a CRM imported user. | [optional] 
**skills** | [**List[LinkedIn1SkillsInner]**](LinkedIn1SkillsInner.md) | A collection of the user&#39;s skills. | [optional] 
**experience** | [**List[LinkedIn1ExperienceInner]**](LinkedIn1ExperienceInner.md) | A collection of the user&#39;s professionnal experiences. | [optional] 
**education** | [**List[LinkedIn1EducationInner]**](LinkedIn1EducationInner.md) | A collection of the user&#39;s education. | [optional] 
**languages** | [**List[LinkedIn1LanguagesInner]**](LinkedIn1LanguagesInner.md) | A collection of the user&#39;s languages. | [optional] 
**certifications** | [**List[LinkedIn1CertificationsInner]**](LinkedIn1CertificationsInner.md) | A collection of the user&#39;s certifications. | [optional] 
**volunteer_experience** | [**List[LinkedIn1VolunteerExperienceInner]**](LinkedIn1VolunteerExperienceInner.md) | A collection of the user&#39;s volunteering experiences. | [optional] 
**projects** | [**List[LinkedIn1ProjectsInner]**](LinkedIn1ProjectsInner.md) | A collection of the user&#39;s projects. | [optional] 
**recommendations** | [**LinkedIn1Recommendations**](LinkedIn1Recommendations.md) |  | [optional] 
**interests** | [**LinkedIn1Interests**](LinkedIn1Interests.md) |  | [optional] 
**throttled_sections** | **List[str]** | A list of sections that are temporary unavailable due to LinkedIn rate limiting. | [optional] 
**recruiting_profile** | [**LinkedIn1RecruitingProfile**](LinkedIn1RecruitingProfile.md) |  | [optional] 

## Example

```python
from unipile.models.linked_in1 import LinkedIn1

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1 from a JSON string
linked_in1_instance = LinkedIn1.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1.to_json())

# convert the object into a dict
linked_in1_dict = linked_in1_instance.to_dict()
# create an instance of LinkedIn1 from a dict
linked_in1_from_dict = LinkedIn1.from_dict(linked_in1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


