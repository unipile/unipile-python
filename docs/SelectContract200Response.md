# SelectContract200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**contract** | [**GetAvailableContracts200ResponseContractsInner**](GetAvailableContracts200ResponseContractsInner.md) |  | 

## Example

```python
from unipile.models.select_contract200_response import SelectContract200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SelectContract200Response from a JSON string
select_contract200_response_instance = SelectContract200Response.from_json(json)
# print the JSON string representation of the object
print(SelectContract200Response.to_json())

# convert the object into a dict
select_contract200_response_dict = select_contract200_response_instance.to_dict()
# create an instance of SelectContract200Response from a dict
select_contract200_response_from_dict = SelectContract200Response.from_dict(select_contract200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


