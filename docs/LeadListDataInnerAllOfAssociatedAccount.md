# LeadListDataInnerAllOfAssociatedAccount

The account associated with the Lead.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the Account. | 
**name** | **str** | The name of the Account. | 
**industry** | **str** | The industry to which the Account belongs. | [optional] 
**location** | **str** | The location of the Account. | [optional] 
**public_identifier** | **str** | The public identifier of the Account. | 
**profile_url** | **str** | The profile URL of the Account. | 
**public_picture_url** | **str** | The profile picture URL of the Account. | [optional] 

## Example

```python
from unipile.models.lead_list_data_inner_all_of_associated_account import LeadListDataInnerAllOfAssociatedAccount

# TODO update the JSON string below
json = "{}"
# create an instance of LeadListDataInnerAllOfAssociatedAccount from a JSON string
lead_list_data_inner_all_of_associated_account_instance = LeadListDataInnerAllOfAssociatedAccount.from_json(json)
# print the JSON string representation of the object
print(LeadListDataInnerAllOfAssociatedAccount.to_json())

# convert the object into a dict
lead_list_data_inner_all_of_associated_account_dict = lead_list_data_inner_all_of_associated_account_instance.to_dict()
# create an instance of LeadListDataInnerAllOfAssociatedAccount from a dict
lead_list_data_inner_all_of_associated_account_from_dict = LeadListDataInnerAllOfAssociatedAccount.from_dict(lead_list_data_inner_all_of_associated_account_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


