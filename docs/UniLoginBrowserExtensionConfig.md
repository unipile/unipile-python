# UniLoginBrowserExtensionConfig

LinkedIn products and managed proxy selection. Credential-bearing custom_proxy configuration is not accepted in this asynchronous flow.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**products** | **List[str]** |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 

## Example

```python
from unipile.models.uni_login_browser_extension_config import UniLoginBrowserExtensionConfig

# TODO update the JSON string below
json = "{}"
# create an instance of UniLoginBrowserExtensionConfig from a JSON string
uni_login_browser_extension_config_instance = UniLoginBrowserExtensionConfig.from_json(json)
# print the JSON string representation of the object
print(UniLoginBrowserExtensionConfig.to_json())

# convert the object into a dict
uni_login_browser_extension_config_dict = uni_login_browser_extension_config_instance.to_dict()
# create an instance of UniLoginBrowserExtensionConfig from a dict
uni_login_browser_extension_config_from_dict = UniLoginBrowserExtensionConfig.from_dict(uni_login_browser_extension_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


