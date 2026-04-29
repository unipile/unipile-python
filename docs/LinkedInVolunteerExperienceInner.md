# LinkedInVolunteerExperienceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organization** | [**LinkedInCertificationsInnerOrganization**](LinkedInCertificationsInnerOrganization.md) |  | [optional] 
**role** | **str** | Role in the experience. | 
**cause** | **str** | Cause of the experience. | [optional] 
**description** | **str** | Description of the experience. | [optional] 
**started_on** | **str** | Start date of the experience in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | End date of the experience in MM/DD/YYYY format. | [optional] 

## Example

```python
from unipile.models.linked_in_volunteer_experience_inner import LinkedInVolunteerExperienceInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInVolunteerExperienceInner from a JSON string
linked_in_volunteer_experience_inner_instance = LinkedInVolunteerExperienceInner.from_json(json)
# print the JSON string representation of the object
print(LinkedInVolunteerExperienceInner.to_json())

# convert the object into a dict
linked_in_volunteer_experience_inner_dict = linked_in_volunteer_experience_inner_instance.to_dict()
# create an instance of LinkedInVolunteerExperienceInner from a dict
linked_in_volunteer_experience_inner_from_dict = LinkedInVolunteerExperienceInner.from_dict(linked_in_volunteer_experience_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


