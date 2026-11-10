# UniLoginBrowserExtension

Connect the active LinkedIn, Instagram or Facebook browser session through the UniLogin extension. No credentials are submitted in this request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to connect with UniLogin. | 
**account_id** | **str** | The existing LinkedIn, Instagram or Facebook Account to reconnect. Omit it to link a new Account. | [optional] 
**account_scope_id** | **str** | The Scope assigned to a newly linked account. Cannot be specified when reconnecting an existing account. | [optional] 
**state** | **str** | State data sent in the account.add or account.reconnect webhook after completion. | [optional] 
**config** | [**UniLoginBrowserExtensionConfig**](UniLoginBrowserExtensionConfig.md) |  | [optional] 
**unilogin** | **bool** | Use the UniLogin extension instead of submitting credentials. | 

## Example

```python
from unipile.models.uni_login_browser_extension import UniLoginBrowserExtension

# TODO update the JSON string below
json = "{}"
# create an instance of UniLoginBrowserExtension from a JSON string
uni_login_browser_extension_instance = UniLoginBrowserExtension.from_json(json)
# print the JSON string representation of the object
print(UniLoginBrowserExtension.to_json())

# convert the object into a dict
uni_login_browser_extension_dict = uni_login_browser_extension_instance.to_dict()
# create an instance of UniLoginBrowserExtension from a dict
uni_login_browser_extension_from_dict = UniLoginBrowserExtension.from_dict(uni_login_browser_extension_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


