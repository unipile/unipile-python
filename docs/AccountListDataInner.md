# AccountListDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the Company. | 
**display_name** | **str** | The display name of the Company. | 
**type** | **str** | The type of the Company. | [optional] 
**specialties** | **List[str]** | A list of the company&#39;s activities. | [optional] 
**public_identifier** | **str** | The public identifier of the Company. | [optional] 
**profile_url** | **str** | The profile URL of the Company. | [optional] 
**public_picture_url** | **str** | The profile picture URL of the Company. | [optional] 
**location** | **str** | The location of the Company. | [optional] 
**industry** | **str** | The industry to which the Company belongs. | 
**summary** | **str** | The summary of the Company&#39;s activities. | [optional] 
**headcount** | **float** | The number of employees of the Company. | [optional] 
**is_hiring_on_linkedin** | **bool** | Whether the Company is hiring on LinkedIn. | [optional] 
**relations_count** | **float** | The number of the relations of the Company. | [optional] 
**lists_count** | **float** | The number of lists you own on which the Company appears. | 
**notes_count** | **float** | The number of notes you own about the Company. | 
**website** | **str** | The webiste URL of the Company. | [optional] 
**founded_on** | **float** | The date on which the Company was founded. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**is_starred** | **bool** | Whether the Company is on starred state. | 
**object** | **str** |  | 
**recommended_lead** | [**AccountListDataInnerRecommendedLead**](AccountListDataInnerRecommendedLead.md) |  | [optional] 

## Example

```python
from unipile.models.account_list_data_inner import AccountListDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of AccountListDataInner from a JSON string
account_list_data_inner_instance = AccountListDataInner.from_json(json)
# print the JSON string representation of the object
print(AccountListDataInner.to_json())

# convert the object into a dict
account_list_data_inner_dict = account_list_data_inner_instance.to_dict()
# create an instance of AccountListDataInner from a dict
account_list_data_inner_from_dict = AccountListDataInner.from_dict(account_list_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


