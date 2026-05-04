# PeopleSearch1DataInner


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
**location** | **str** | The location of the User. | [optional] 
**headline** | **str** | The headline of the User. | 
**network_distance** | [**PeopleSearch1DataInnerNetworkDistance**](PeopleSearch1DataInnerNetworkDistance.md) |  | 
**can_send_inmail** | **bool** | Whether it is possible to send an inMail to this User. | [optional] 
**product** | **str** |  | 
**shared_relations_count** | **float** | The number of relations that you share with the User. | [optional] 
**summary** | **str** | The summary of the User. | [optional] 
**has_been_viewed** | **bool** | Whether you have already visited the User&#39;s profile. | 
**has_been_saved** | **bool** | Whether the User has been saved to a list. | 
**has_posted_recently** | **bool** | Whether the User has posted recently. | 
**has_viewed_your_profile** | **bool** | Whether the User has already visited your profile. | 
**was_hired_recently** | **bool** | Whether the User was hired recently. | 
**was_promoted_recently** | **bool** | Whether the User was promoted recently. | 
**follows_your_company** | **bool** | Whether the User is folliwing your company. | 
**is_premium** | **bool** | Whether the User has a premium subscription. | 
**is_past_colleague** | **bool** | Whether the User is a past colleague of yours. | 
**is_open_profile** | **bool** | Whether the User has an Open Profile. The Open Profile feature allows anyone on LinkedIn to contact a Premium member for free. | 
**websites** | **List[Optional[str]]** | A list of websites of the User. | [optional] 
**addresses** | **List[Optional[str]]** | A list of addresses of the User. | [optional] 
**contact_info** | [**PeopleSearch1DataInnerContactInfo**](PeopleSearch1DataInnerContactInfo.md) |  | 
**latest_contact** | [**PeopleSearch1DataInnerLatestContact**](PeopleSearch1DataInnerLatestContact.md) |  | [optional] 
**lists_count** | **float** | The number of lists you own on which the User appears. | 
**notes_count** | **float** | The number of notes you own about the User. | 
**social_handles** | [**PeopleSearch1DataInnerSocialHandles**](PeopleSearch1DataInnerSocialHandles.md) |  | [optional] 
**education** | [**List[FullProfileEducationInner]**](FullProfileEducationInner.md) |  | 
**skills** | [**List[FullProfileSkillsInner]**](FullProfileSkillsInner.md) |  | 
**work_experience** | [**List[PartialProfileWorkExperienceInner]**](PartialProfileWorkExperienceInner.md) |  | 
**languages** | [**List[LinkedInLanguagesInner]**](LinkedInLanguagesInner.md) |  | 
**volunteering** | [**List[LinkedInVolunteerExperienceInner]**](LinkedInVolunteerExperienceInner.md) |  | 

## Example

```python
from unipile.models.people_search1_data_inner import PeopleSearch1DataInner

# TODO update the JSON string below
json = "{}"
# create an instance of PeopleSearch1DataInner from a JSON string
people_search1_data_inner_instance = PeopleSearch1DataInner.from_json(json)
# print the JSON string representation of the object
print(PeopleSearch1DataInner.to_json())

# convert the object into a dict
people_search1_data_inner_dict = people_search1_data_inner_instance.to_dict()
# create an instance of PeopleSearch1DataInner from a dict
people_search1_data_inner_from_dict = PeopleSearch1DataInner.from_dict(people_search1_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


