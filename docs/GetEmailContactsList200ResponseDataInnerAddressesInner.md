# GetEmailContactsList200ResponseDataInnerAddressesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**city** | **str** | City of the physical address. | 
**country** | **str** | Country of the physical address. | 
**postal_code** | **str** | Postal or ZIP code of the physical address. | 
**state** | **str** | State or province of the physical address. | 
**street_address** | **str** | Street address line. | 
**type** | **str** | Type of address (e.g. personal, business, other). | 

## Example

```python
from unipile.models.get_email_contacts_list200_response_data_inner_addresses_inner import GetEmailContactsList200ResponseDataInnerAddressesInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetEmailContactsList200ResponseDataInnerAddressesInner from a JSON string
get_email_contacts_list200_response_data_inner_addresses_inner_instance = GetEmailContactsList200ResponseDataInnerAddressesInner.from_json(json)
# print the JSON string representation of the object
print(GetEmailContactsList200ResponseDataInnerAddressesInner.to_json())

# convert the object into a dict
get_email_contacts_list200_response_data_inner_addresses_inner_dict = get_email_contacts_list200_response_data_inner_addresses_inner_instance.to_dict()
# create an instance of GetEmailContactsList200ResponseDataInnerAddressesInner from a dict
get_email_contacts_list200_response_data_inner_addresses_inner_from_dict = GetEmailContactsList200ResponseDataInnerAddressesInner.from_dict(get_email_contacts_list200_response_data_inner_addresses_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


