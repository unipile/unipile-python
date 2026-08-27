# ScopedAccountAPIKey


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | An internal name used to identify the API Key. | 
**expires_at** | **str** | The date and time when the API Key expires, in ISO 8601 format. | 
**access** | [**ScopedAccountAPIKeyAccess**](ScopedAccountAPIKeyAccess.md) |  | 

## Example

```python
from unipile.models.scoped_account_api_key import ScopedAccountAPIKey

# TODO update the JSON string below
json = "{}"
# create an instance of ScopedAccountAPIKey from a JSON string
scoped_account_api_key_instance = ScopedAccountAPIKey.from_json(json)
# print the JSON string representation of the object
print(ScopedAccountAPIKey.to_json())

# convert the object into a dict
scoped_account_api_key_dict = scoped_account_api_key_instance.to_dict()
# create an instance of ScopedAccountAPIKey from a dict
scoped_account_api_key_from_dict = ScopedAccountAPIKey.from_dict(scoped_account_api_key_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


