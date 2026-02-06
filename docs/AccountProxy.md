# AccountProxy

The proxy used for the account.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**country** | **str** |  | 
**auto_proxy** | **bool** | Whether the proxy was set automatically by Unipile. | 

## Example

```python
from unipile.models.account_proxy import AccountProxy

# TODO update the JSON string below
json = "{}"
# create an instance of AccountProxy from a JSON string
account_proxy_instance = AccountProxy.from_json(json)
# print the JSON string representation of the object
print(AccountProxy.to_json())

# convert the object into a dict
account_proxy_dict = account_proxy_instance.to_dict()
# create an instance of AccountProxy from a dict
account_proxy_from_dict = AccountProxy.from_dict(account_proxy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


