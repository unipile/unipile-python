# AccountInitialSync

Sync details if the account has initial sync enabled.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | The state of an account’s initial provider sync.   - &#x60;pending&#x60;sync hasn’t started yet.   - &#x60;running&#x60; sync is currently in progress.   - &#x60;failed&#x60; sync could not be completed due to an error.   - &#x60;completed&#x60; sync finished successfully.   . | 
**started_at** | **str** | The date and time the initial sync started. | [optional] 

## Example

```python
from unipile.models.account_initial_sync import AccountInitialSync

# TODO update the JSON string below
json = "{}"
# create an instance of AccountInitialSync from a JSON string
account_initial_sync_instance = AccountInitialSync.from_json(json)
# print the JSON string representation of the object
print(AccountInitialSync.to_json())

# convert the object into a dict
account_initial_sync_dict = account_initial_sync_instance.to_dict()
# create an instance of AccountInitialSync from a dict
account_initial_sync_from_dict = AccountInitialSync.from_dict(account_initial_sync_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


