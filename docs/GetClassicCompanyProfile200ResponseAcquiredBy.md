# GetClassicCompanyProfile200ResponseAcquiredBy


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the Company for the provider. | 
**name** | **str** | The name of the Company. | 
**public_identifier** | **str** | The public identifier of the Company. | 
**profile_url** | **str** | The public profile URL of the Company. | 

## Example

```python
from unipile.models.get_classic_company_profile200_response_acquired_by import GetClassicCompanyProfile200ResponseAcquiredBy

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicCompanyProfile200ResponseAcquiredBy from a JSON string
get_classic_company_profile200_response_acquired_by_instance = GetClassicCompanyProfile200ResponseAcquiredBy.from_json(json)
# print the JSON string representation of the object
print(GetClassicCompanyProfile200ResponseAcquiredBy.to_json())

# convert the object into a dict
get_classic_company_profile200_response_acquired_by_dict = get_classic_company_profile200_response_acquired_by_instance.to_dict()
# create an instance of GetClassicCompanyProfile200ResponseAcquiredBy from a dict
get_classic_company_profile200_response_acquired_by_from_dict = GetClassicCompanyProfile200ResponseAcquiredBy.from_dict(get_classic_company_profile200_response_acquired_by_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


