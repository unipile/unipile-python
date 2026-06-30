# ContractSelection

The user must pick a contract from a list to activate the correct features and complete authentication.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**contracts** | [**List[CreateRecruiterHiringProjectRequestJobTitle]**](CreateRecruiterHiringProjectRequestJobTitle.md) | A list of contracts to choose from. | 

## Example

```python
from unipile.models.contract_selection import ContractSelection

# TODO update the JSON string below
json = "{}"
# create an instance of ContractSelection from a JSON string
contract_selection_instance = ContractSelection.from_json(json)
# print the JSON string representation of the object
print(ContractSelection.to_json())

# convert the object into a dict
contract_selection_dict = contract_selection_instance.to_dict()
# create an instance of ContractSelection from a dict
contract_selection_from_dict = ContractSelection.from_dict(contract_selection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


