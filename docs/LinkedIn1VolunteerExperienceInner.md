# LinkedIn1VolunteerExperienceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**organization** | [**LinkedIn1CertificationsInnerOrganization**](LinkedIn1CertificationsInnerOrganization.md) |  | [optional] 
**role** | **str** | Role in the experience. | 
**cause** | **str** | Cause of the experience. | [optional] 
**description** | **str** | Description of the experience. | [optional] 
**started_on** | **str** | Start date of the experience in MM/DD/YYYY format. | [optional] 
**ended_on** | **str** | End date of the experience in MM/DD/YYYY format. | [optional] 

## Example

```python
from unipile.models.linked_in1_volunteer_experience_inner import LinkedIn1VolunteerExperienceInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1VolunteerExperienceInner from a JSON string
linked_in1_volunteer_experience_inner_instance = LinkedIn1VolunteerExperienceInner.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1VolunteerExperienceInner.to_json())

# convert the object into a dict
linked_in1_volunteer_experience_inner_dict = linked_in1_volunteer_experience_inner_instance.to_dict()
# create an instance of LinkedIn1VolunteerExperienceInner from a dict
linked_in1_volunteer_experience_inner_from_dict = LinkedIn1VolunteerExperienceInner.from_dict(linked_in1_volunteer_experience_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


