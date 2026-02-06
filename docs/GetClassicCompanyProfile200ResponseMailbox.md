# GetClassicCompanyProfile200ResponseMailbox

The mailbox informations of the Company.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the mailbox. Should be used to start a chat with the Company provided that messaging is enabled. | 
**enabled** | **bool** | Whether the Company has enabled messaging. | 

## Example

```python
from unipile.models.get_classic_company_profile200_response_mailbox import GetClassicCompanyProfile200ResponseMailbox

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicCompanyProfile200ResponseMailbox from a JSON string
get_classic_company_profile200_response_mailbox_instance = GetClassicCompanyProfile200ResponseMailbox.from_json(json)
# print the JSON string representation of the object
print(GetClassicCompanyProfile200ResponseMailbox.to_json())

# convert the object into a dict
get_classic_company_profile200_response_mailbox_dict = get_classic_company_profile200_response_mailbox_instance.to_dict()
# create an instance of GetClassicCompanyProfile200ResponseMailbox from a dict
get_classic_company_profile200_response_mailbox_from_dict = GetClassicCompanyProfile200ResponseMailbox.from_dict(get_classic_company_profile200_response_mailbox_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


