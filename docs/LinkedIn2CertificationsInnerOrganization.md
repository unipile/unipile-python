# LinkedIn2CertificationsInnerOrganization


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the company. | [optional] 
**id** | **str** | Unique identifier of the company. | 
**public_identifier** | **str** | Public identifier of the company. | [optional] 
**picture_url** | **str** | Public url to the profile picture of the company. | [optional] 
**profile_url** | **str** | Public url to the profile of the company. | [optional] 
**industries** | **List[str]** | Industry types of the company. | [optional] 
**headcount_range** | [**LinkedIn2ExperienceInnerCompanyHeadcountRange**](LinkedIn2ExperienceInnerCompanyHeadcountRange.md) |  | [optional] 

## Example

```python
from unipile.models.linked_in2_certifications_inner_organization import LinkedIn2CertificationsInnerOrganization

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn2CertificationsInnerOrganization from a JSON string
linked_in2_certifications_inner_organization_instance = LinkedIn2CertificationsInnerOrganization.from_json(json)
# print the JSON string representation of the object
print(LinkedIn2CertificationsInnerOrganization.to_json())

# convert the object into a dict
linked_in2_certifications_inner_organization_dict = linked_in2_certifications_inner_organization_instance.to_dict()
# create an instance of LinkedIn2CertificationsInnerOrganization from a dict
linked_in2_certifications_inner_organization_from_dict = LinkedIn2CertificationsInnerOrganization.from_dict(linked_in2_certifications_inner_organization_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


