# GlobalAccountAPIKey


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | An internal name used to identify the API Key. | 
**expires_at** | **str** | The date and time when the API Key expires, in ISO 8601 format. | 
**access** | [**GlobalAccountAPIKeyAccess**](GlobalAccountAPIKeyAccess.md) |  | 

## Example

```python
from unipile.models.global_account_api_key import GlobalAccountAPIKey

# TODO update the JSON string below
json = "{}"
# create an instance of GlobalAccountAPIKey from a JSON string
global_account_api_key_instance = GlobalAccountAPIKey.from_json(json)
# print the JSON string representation of the object
print(GlobalAccountAPIKey.to_json())

# convert the object into a dict
global_account_api_key_dict = global_account_api_key_instance.to_dict()
# create an instance of GlobalAccountAPIKey from a dict
global_account_api_key_from_dict = GlobalAccountAPIKey.from_dict(global_account_api_key_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


