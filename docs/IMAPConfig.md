# IMAPConfig

IMAP specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy**](CustomProxy.md) |  | [optional] 
**initial_sync_enable** | **bool** | Whether initial sync is enabled. Defaults to false for new accounts. When reconnecting, omitting this field preserves the current setting. Re-enabling starts a fresh initial sync. Initial sync is required for advanced search. Read more in the Synced Accounts guide. | [optional] 

## Example

```python
from unipile.models.imap_config import IMAPConfig

# TODO update the JSON string below
json = "{}"
# create an instance of IMAPConfig from a JSON string
imap_config_instance = IMAPConfig.from_json(json)
# print the JSON string representation of the object
print(IMAPConfig.to_json())

# convert the object into a dict
imap_config_dict = imap_config_instance.to_dict()
# create an instance of IMAPConfig from a dict
imap_config_from_dict = IMAPConfig.from_dict(imap_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


