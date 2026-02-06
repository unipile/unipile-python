# GetUserProfile200ResponseSpecificsAllOfAnyOf

Specific options to apply if the provider of the targeted account is Linkedin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**member_urn** | **str** | Member URN of the user. | 
**can_send_inmail** | **bool** | Whether the user can be reached with inmails. | [optional] 
**network_distance** | **str** | Network distance to a User.       &#x60;SELF&#x60;: Yourself.       &#x60;FIRST_DEGREE&#x60;: 1st degree connection.       &#x60;SECOND_DEGREE&#x60;: 2nd degree connection (connection of a 1st degree).       &#x60;THIRD_DEGREE&#x60;: 3rd degree connection (connection of a 2nd degree).       &#x60;OUT_OF_NETWORK&#x60;: Unreachable user.&#39; | 
**default_locale** | **str** | Default language of the user&#39;s profile. | [optional] 
**supported_locales** | **List[str]** |  | [optional] 
**websites** | **List[str]** |  | [optional] 
**notify_visit_token** | **str** | Payload that should be passed to the Notify profile visit route in order to notify the visit. | [optional] 
**is_open_profile** | **bool** | Whether the user has an open profile (can be reached with free inmails). | [optional] 
**is_premium** | **bool** | Whether the user has a premium subscription. | [optional] 
**is_influencer** | **bool** | Whether the user is an influencer. | [optional] 
**is_creator** | **bool** | Whether the user is a creator. | [optional] 
**is_hiring** | **bool** | Whether the user is hiring. | [optional] 
**is_open_to_work** | **bool** | Whether the user is open to work. | [optional] 
**is_saved_lead** | **bool** | Whether the user is a saved lead. | [optional] 
**is_crm_imported** | **bool** | Whether the user is a CRM imported user. | [optional] 
**shared_relations_count** | **float** | Number of relations shared with the user. | [optional] 
**skills** | [**List[GetUserProfile200ResponseSpecificsAllOfAnyOfSkillsInner]**](GetUserProfile200ResponseSpecificsAllOfAnyOfSkillsInner.md) |  | [optional] 
**experience** | [**List[GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInner]**](GetUserProfile200ResponseSpecificsAllOfAnyOfExperienceInner.md) |  | [optional] 
**education** | [**List[GetUserProfile200ResponseSpecificsAllOfAnyOfEducationInner]**](GetUserProfile200ResponseSpecificsAllOfAnyOfEducationInner.md) |  | [optional] 
**languages** | [**List[GetUserProfile200ResponseSpecificsAllOfAnyOfLanguagesInner]**](GetUserProfile200ResponseSpecificsAllOfAnyOfLanguagesInner.md) |  | [optional] 
**certifications** | [**List[GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInner]**](GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInner.md) |  | [optional] 
**volunteer_experience** | [**List[GetUserProfile200ResponseSpecificsAllOfAnyOfVolunteerExperienceInner]**](GetUserProfile200ResponseSpecificsAllOfAnyOfVolunteerExperienceInner.md) |  | [optional] 
**projects** | [**List[GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInner]**](GetUserProfile200ResponseSpecificsAllOfAnyOfProjectsInner.md) |  | [optional] 
**recommendations** | [**GetUserProfile200ResponseSpecificsAllOfAnyOfRecommendations**](GetUserProfile200ResponseSpecificsAllOfAnyOfRecommendations.md) |  | [optional] 
**throttled_sections** | **List[str]** | A list of sections that are temporary unavailable due to LinkedIn rate limiting. | [optional] 

## Example

```python
from unipile.models.get_user_profile200_response_specifics_all_of_any_of import GetUserProfile200ResponseSpecificsAllOfAnyOf

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOf from a JSON string
get_user_profile200_response_specifics_all_of_any_of_instance = GetUserProfile200ResponseSpecificsAllOfAnyOf.from_json(json)
# print the JSON string representation of the object
print(GetUserProfile200ResponseSpecificsAllOfAnyOf.to_json())

# convert the object into a dict
get_user_profile200_response_specifics_all_of_any_of_dict = get_user_profile200_response_specifics_all_of_any_of_instance.to_dict()
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOf from a dict
get_user_profile200_response_specifics_all_of_any_of_from_dict = GetUserProfile200ResponseSpecificsAllOfAnyOf.from_dict(get_user_profile200_response_specifics_all_of_any_of_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


