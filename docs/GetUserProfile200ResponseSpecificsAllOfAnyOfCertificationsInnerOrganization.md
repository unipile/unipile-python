# GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInnerOrganization


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the company. | [optional] 
**id** | **str** | Unique identifier of the company. | 
**public_identifier** | **str** | Public identifier of the company. | [optional] 
**picture_url** | **str** | Public url to the profile picture of the company. | [optional] 
**profile_url** | **str** | Public url to the profile of the company. | [optional] 
**industries** | **List[str]** | Industry types of the company. | [optional] 

## Example

```python
from unipile.models.get_user_profile200_response_specifics_all_of_any_of_certifications_inner_organization import GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInnerOrganization

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInnerOrganization from a JSON string
get_user_profile200_response_specifics_all_of_any_of_certifications_inner_organization_instance = GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInnerOrganization.from_json(json)
# print the JSON string representation of the object
print(GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInnerOrganization.to_json())

# convert the object into a dict
get_user_profile200_response_specifics_all_of_any_of_certifications_inner_organization_dict = get_user_profile200_response_specifics_all_of_any_of_certifications_inner_organization_instance.to_dict()
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInnerOrganization from a dict
get_user_profile200_response_specifics_all_of_any_of_certifications_inner_organization_from_dict = GetUserProfile200ResponseSpecificsAllOfAnyOfCertificationsInnerOrganization.from_dict(get_user_profile200_response_specifics_all_of_any_of_certifications_inner_organization_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


