# LeadListDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the user. | 
**member_id** | **str** | The LinkedIn internal member ID of the user. | [optional] 
**display_name** | **str** | The display name of the User. | 
**public_identifier** | **str** | The public identifier of the User. | [optional] 
**profile_url** | **str** | The profile URL of the User. | [optional] 
**public_picture_url** | **str** | The public picture URL of the User. | [optional] 
**public_picture_url_large** | **str** | The public picture URL of the User in large size. | [optional] 
**relations_count** | **float** | The number of relations of the User. | [optional] 
**location** | **str** | The location of the User. | [optional] 
**headline** | **str** | The headline of the User. | 
**network_distance** | [**PeopleSearch1DataInnerNetworkDistance**](PeopleSearch1DataInnerNetworkDistance.md) |  | 
**can_send_inmail** | **bool** | Whether it is possible to send an inMail to this User. | [optional] 
**shared_relations_count** | **float** | The number of relations that you share with the User. | [optional] 
**summary** | **str** | The summary of the User. | [optional] 
**has_posted_recently** | **bool** | Whether the User has posted recently. | 
**has_viewed_your_profile** | **bool** | Whether the User has already visited your profile. | 
**was_hired_recently** | **bool** | Whether the User was hired recently. | 
**was_promoted_recently** | **bool** | Whether the User was promoted recently. | 
**follows_your_company** | **bool** | Whether the User is folliwing your company. | 
**is_premium** | **bool** | Whether the User has a premium subscription. | 
**is_past_colleague** | **bool** | Whether the User is a past colleague of yours. | 
**is_open_profile** | **bool** | Whether the User has an Open Profile. The Open Profile feature allows anyone on LinkedIn to contact a Premium member for free. | 
**websites** | **List[str]** | A list of websites of the User. | [optional] 
**addresses** | **List[str]** | A list of addresses of the User. | [optional] 
**contact_info** | [**LeadListDataInnerAllOfAllOfContactInfo**](LeadListDataInnerAllOfAllOfContactInfo.md) |  | 
**latest_contact** | [**PeopleSearch1DataInnerLatestContact**](PeopleSearch1DataInnerLatestContact.md) |  | [optional] 
**lists_count** | **float** | The number of lists you own on which the User appears. | 
**notes_count** | **float** | The number of notes you own about the User. | 
**social_handles** | [**LeadListDataInnerAllOfAllOfSocialHandles**](LeadListDataInnerAllOfAllOfSocialHandles.md) |  | [optional] 
**education** | [**List[FullProfileEducationInner]**](FullProfileEducationInner.md) |  | 
**skills** | [**List[FullProfileSkillsInner]**](FullProfileSkillsInner.md) |  | 
**work_experience** | [**List[PartialProfileWorkExperienceInner]**](PartialProfileWorkExperienceInner.md) |  | 
**languages** | [**List[LinkedInLanguagesInner]**](LinkedInLanguagesInner.md) |  | 
**volunteering** | [**List[LinkedInVolunteerExperienceInner]**](LinkedInVolunteerExperienceInner.md) |  | 
**object** | **str** |  | 
**saved_at** | **str** | The date on which the Lead was saved. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**associated_account** | [**LeadListDataInnerAllOfAssociatedAccount**](LeadListDataInnerAllOfAssociatedAccount.md) |  | [optional] 

## Example

```python
from unipile.models.lead_list_data_inner import LeadListDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of LeadListDataInner from a JSON string
lead_list_data_inner_instance = LeadListDataInner.from_json(json)
# print the JSON string representation of the object
print(LeadListDataInner.to_json())

# convert the object into a dict
lead_list_data_inner_dict = lead_list_data_inner_instance.to_dict()
# create an instance of LeadListDataInner from a dict
lead_list_data_inner_from_dict = LeadListDataInner.from_dict(lead_list_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


