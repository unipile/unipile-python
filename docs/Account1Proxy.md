# Account1Proxy

The proxy used for the account.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**country** | **str** | The country of the proxy. If null, the proxy has no defined country. | 
**auto_proxy** | **bool** | Whether the proxy was set automatically by Unipile. | 

## Example

```python
from unipile.models.account1_proxy import Account1Proxy

# TODO update the JSON string below
json = "{}"
# create an instance of Account1Proxy from a JSON string
account1_proxy_instance = Account1Proxy.from_json(json)
# print the JSON string representation of the object
print(Account1Proxy.to_json())

# convert the object into a dict
account1_proxy_dict = account1_proxy_instance.to_dict()
# create an instance of Account1Proxy from a dict
account1_proxy_from_dict = Account1Proxy.from_dict(account1_proxy_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


