# GetAvailableContracts200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**contracts** | [**List[GetAvailableContracts200ResponseContractsInner]**](GetAvailableContracts200ResponseContractsInner.md) |  | 

## Example

```python
from unipile.models.get_available_contracts200_response import GetAvailableContracts200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetAvailableContracts200Response from a JSON string
get_available_contracts200_response_instance = GetAvailableContracts200Response.from_json(json)
# print the JSON string representation of the object
print(GetAvailableContracts200Response.to_json())

# convert the object into a dict
get_available_contracts200_response_dict = get_available_contracts200_response_instance.to_dict()
# create an instance of GetAvailableContracts200Response from a dict
get_available_contracts200_response_from_dict = GetAvailableContracts200Response.from_dict(get_available_contracts200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


