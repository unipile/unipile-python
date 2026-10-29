# SyncAccount202Response

Confirmation that a full history synchronization was requested. Completion is asynchronous.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | Object type identifier, always \&quot;AccountSyncRequested\&quot;. | 
**request_id** | **str** | Identifier of the history synchronization request sent to the provider. | 

## Example

```python
from unipile.models.sync_account202_response import SyncAccount202Response

# TODO update the JSON string below
json = "{}"
# create an instance of SyncAccount202Response from a JSON string
sync_account202_response_instance = SyncAccount202Response.from_json(json)
# print the JSON string representation of the object
print(SyncAccount202Response.to_json())

# convert the object into a dict
sync_account202_response_dict = sync_account202_response_instance.to_dict()
# create an instance of SyncAccount202Response from a dict
sync_account202_response_from_dict = SyncAccount202Response.from_dict(sync_account202_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


