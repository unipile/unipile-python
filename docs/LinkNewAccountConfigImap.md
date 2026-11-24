# LinkNewAccountConfigImap

IMAP specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy**](CustomProxy.md) |  | [optional] 
**initial_sync_enable** | **bool** | Whether initial sync is enabled. Defaults to false for new accounts. When reconnecting, omitting this field preserves the current setting. Re-enabling starts a fresh initial sync. Initial sync is required for advanced search. Read more in the Synced Accounts guide. | [optional] 

## Example

```python
from unipile.models.link_new_account_config_imap import LinkNewAccountConfigImap

# TODO update the JSON string below
json = "{}"
# create an instance of LinkNewAccountConfigImap from a JSON string
link_new_account_config_imap_instance = LinkNewAccountConfigImap.from_json(json)
# print the JSON string representation of the object
print(LinkNewAccountConfigImap.to_json())

# convert the object into a dict
link_new_account_config_imap_dict = link_new_account_config_imap_instance.to_dict()
# create an instance of LinkNewAccountConfigImap from a dict
link_new_account_config_imap_from_dict = LinkNewAccountConfigImap.from_dict(link_new_account_config_imap_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


