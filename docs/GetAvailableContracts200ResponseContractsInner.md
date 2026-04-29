# GetAvailableContracts200ResponseContractsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**selected** | **bool** |  | 
**id** | **str** | The ID of the contract. | 
**name** | **str** | The name of the contract. | 
**description** | **str** | The description of the contract. | [optional] 

## Example

```python
from unipile.models.get_available_contracts200_response_contracts_inner import GetAvailableContracts200ResponseContractsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetAvailableContracts200ResponseContractsInner from a JSON string
get_available_contracts200_response_contracts_inner_instance = GetAvailableContracts200ResponseContractsInner.from_json(json)
# print the JSON string representation of the object
print(GetAvailableContracts200ResponseContractsInner.to_json())

# convert the object into a dict
get_available_contracts200_response_contracts_inner_dict = get_available_contracts200_response_contracts_inner_instance.to_dict()
# create an instance of GetAvailableContracts200ResponseContractsInner from a dict
get_available_contracts200_response_contracts_inner_from_dict = GetAvailableContracts200ResponseContractsInner.from_dict(get_available_contracts200_response_contracts_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


