# GlobalAccountAPIKeyAccess

The Account access boundary of the API Key.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Grants access to every Account in the Application without management permissions. | 

## Example

```python
from unipile.models.global_account_api_key_access import GlobalAccountAPIKeyAccess

# TODO update the JSON string below
json = "{}"
# create an instance of GlobalAccountAPIKeyAccess from a JSON string
global_account_api_key_access_instance = GlobalAccountAPIKeyAccess.from_json(json)
# print the JSON string representation of the object
print(GlobalAccountAPIKeyAccess.to_json())

# convert the object into a dict
global_account_api_key_access_dict = global_account_api_key_access_instance.to_dict()
# create an instance of GlobalAccountAPIKeyAccess from a dict
global_account_api_key_access_from_dict = GlobalAccountAPIKeyAccess.from_dict(global_account_api_key_access_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


