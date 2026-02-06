# AccountListDataInnerRecommendedLead

A recommended lead associated with the Account.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the User. | 
**display_name** | **str** | The display name of the User. | 
**public_identifier** | **str** | The public identifier of the User. | [optional] 
**profile_url** | **str** | The profile URL of the User. | [optional] 
**public_picture_url** | **str** | The profile picture URL of the User. | [optional] 
**relations_count** | **float** | The number of the relations of the User. | [optional] 
**shared_relations_count** | **float** | The number of relations that you share with the User. | [optional] 
**location** | **str** | The location of the User. | 
**headline** | **str** | The headline of the User. | 
**summary** | **str** | The summary of the User. | [optional] 
**has_posted_recently** | **bool** | Whether the User has posted recently. | 
**has_viewed_your_profile** | **bool** | Whether the User has already visited your profile. | 
**was_hired_recently** | **bool** | Whether the User was hired recently. | 
**was_promoted_recently** | **bool** | Whether the User was promoted recently. | 
**follows_your_company** | **bool** | Whether the User is folliwing your company. | 
**is_premium** | **bool** | Whether the User has a premium subscription. | 
**is_past_colleague** | **bool** | Whether the User is a past colleague of yours. | 
**is_open_profile** | **bool** | Whether the User has an Open Profile. The Open Profile feature allows anyone on LinkedIn to contact a Premium member for free. | 
**can_send_inmail** | **bool** | Whether it is possible to send an inMail to this User. | 
**websites** | **List[str]** | A list of websites of the User. | [optional] 
**addresses** | **List[str]** | A list of addresses of the User. | [optional] 
**contact_info** | [**LeadListDataInnerAllOfAllOfContactInfo**](LeadListDataInnerAllOfAllOfContactInfo.md) |  | 
**latest_contact** | [**PeopleSearch1DataInnerLatestContact**](PeopleSearch1DataInnerLatestContact.md) |  | [optional] 
**lists_count** | **float** | The number of lists you own on which the User appears. | 
**notes_count** | **float** | The number of notes you own about the User. | 
**social_networks** | [**PeopleSearch1DataInnerSocialNetworks**](PeopleSearch1DataInnerSocialNetworks.md) |  | 
**network_distance** | **str** | Network distance to a User.       &#x60;SELF&#x60;: Yourself.       &#x60;FIRST_DEGREE&#x60;: 1st degree connection.       &#x60;SECOND_DEGREE&#x60;: 2nd degree connection (connection of a 1st degree).       &#x60;THIRD_DEGREE&#x60;: 3rd degree connection (connection of a 2nd degree).       &#x60;OUT_OF_NETWORK&#x60;: Unreachable user.&#39; | 
**education** | [**List[FullProfileEducationInner]**](FullProfileEducationInner.md) |  | 
**skills** | [**List[FullProfileSkillsInner]**](FullProfileSkillsInner.md) |  | 
**work_experience** | [**List[PartialProfileWorkExperienceInner]**](PartialProfileWorkExperienceInner.md) |  | 
**languages** | [**List[GetUserProfile200ResponseSpecificsAllOfAnyOfLanguagesInner]**](GetUserProfile200ResponseSpecificsAllOfAnyOfLanguagesInner.md) |  | 
**volunteering** | [**List[GetUserProfile200ResponseSpecificsAllOfAnyOfVolunteerExperienceInner]**](GetUserProfile200ResponseSpecificsAllOfAnyOfVolunteerExperienceInner.md) |  | 
**object** | **str** |  | 

## Example

```python
from unipile.models.account_list_data_inner_recommended_lead import AccountListDataInnerRecommendedLead

# TODO update the JSON string below
json = "{}"
# create an instance of AccountListDataInnerRecommendedLead from a JSON string
account_list_data_inner_recommended_lead_instance = AccountListDataInnerRecommendedLead.from_json(json)
# print the JSON string representation of the object
print(AccountListDataInnerRecommendedLead.to_json())

# convert the object into a dict
account_list_data_inner_recommended_lead_dict = account_list_data_inner_recommended_lead_instance.to_dict()
# create an instance of AccountListDataInnerRecommendedLead from a dict
account_list_data_inner_recommended_lead_from_dict = AccountListDataInnerRecommendedLead.from_dict(account_list_data_inner_recommended_lead_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


