# ScopedAccountAPIKeyAccess

The Account access boundary of the API Key.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Restricts access to Accounts permanently assigned to one Scope. | 
**scope_id** | **str** | The ID of the active Scope that the API Key can access. | 

## Example

```python
from unipile.models.scoped_account_api_key_access import ScopedAccountAPIKeyAccess

# TODO update the JSON string below
json = "{}"
# create an instance of ScopedAccountAPIKeyAccess from a JSON string
scoped_account_api_key_access_instance = ScopedAccountAPIKeyAccess.from_json(json)
# print the JSON string representation of the object
print(ScopedAccountAPIKeyAccess.to_json())

# convert the object into a dict
scoped_account_api_key_access_dict = scoped_account_api_key_access_instance.to_dict()
# create an instance of ScopedAccountAPIKeyAccess from a dict
scoped_account_api_key_access_from_dict = ScopedAccountAPIKeyAccess.from_dict(scoped_account_api_key_access_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


