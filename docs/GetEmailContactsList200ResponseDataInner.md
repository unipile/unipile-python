# GetEmailContactsList200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | Object type identifier, always \&quot;Contact\&quot;. | 
**id** | **str** | Unique identifier of the contact. | 
**picture_url** | **str** | URL of the profile picture of the contact. | [optional] 
**first_name** | **str** | First name of the user. | [optional] 
**middle_name** | **str** | Middle name of the contact. | [optional] 
**last_name** | **str** | Last name of the user. | [optional] 
**display_name** | **str** | Display name of the user. | [optional] 
**suffix** | **str** | Name suffix (e.g. Jr., Sr., PhD). | [optional] 
**birth_date** | **str** | Birth date of the user. | [optional] 
**company_name** | **str** | Name of the company the contact works for. | [optional] 
**job_title** | **str** | Job title or position of the contact. | [optional] 
**manager_name** | **str** | Name of the contact&#39;s manager. | [optional] 
**office_location** | **str** | Office location or building of the contact. | [optional] 
**notes** | **str** | Free-text notes associated with the contact. | [optional] 
**emails** | **List[Optional[str]]** | List of user email addresses. | [optional] 
**phone_numbers** | **List[Optional[str]]** | List of user phone numbers. | [optional] 
**social_handles** | [**GetEmailContactsList200ResponseDataInnerSocialHandles**](GetEmailContactsList200ResponseDataInnerSocialHandles.md) |  | [optional] 
**addresses** | [**List[GetEmailContactsList200ResponseDataInnerAddressesInner]**](GetEmailContactsList200ResponseDataInnerAddressesInner.md) | List of physical addresses associated with the contact. | [optional] 
**websites** | **List[Optional[str]]** | List of user websites. | [optional] 
**groups** | [**List[GetEmailContactsList200ResponseDataInnerGroupsInner]**](GetEmailContactsList200ResponseDataInnerGroupsInner.md) | List of groups the contact belongs to. | [optional] 

## Example

```python
from unipile.models.get_email_contacts_list200_response_data_inner import GetEmailContactsList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetEmailContactsList200ResponseDataInner from a JSON string
get_email_contacts_list200_response_data_inner_instance = GetEmailContactsList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetEmailContactsList200ResponseDataInner.to_json())

# convert the object into a dict
get_email_contacts_list200_response_data_inner_dict = get_email_contacts_list200_response_data_inner_instance.to_dict()
# create an instance of GetEmailContactsList200ResponseDataInner from a dict
get_email_contacts_list200_response_data_inner_from_dict = GetEmailContactsList200ResponseDataInner.from_dict(get_email_contacts_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


