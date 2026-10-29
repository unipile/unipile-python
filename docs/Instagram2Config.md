# Instagram2Config

Instagram specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 
**allow_methods** | **List[str]** | The authentication methods to show in the hosted auth.           &#x60;credentials&#x60; : Credentials Authentication           &#x60;cookies&#x60; : Cookies Authentication           &#x60;unilogin&#x60; : Connect the active browser session through the UniLogin extension          | [optional] [default to ["credentials","unilogin"]]

## Example

```python
from unipile.models.instagram2_config import Instagram2Config

# TODO update the JSON string below
json = "{}"
# create an instance of Instagram2Config from a JSON string
instagram2_config_instance = Instagram2Config.from_json(json)
# print the JSON string representation of the object
print(Instagram2Config.to_json())

# convert the object into a dict
instagram2_config_dict = instagram2_config_instance.to_dict()
# create an instance of Instagram2Config from a dict
instagram2_config_from_dict = Instagram2Config.from_dict(instagram2_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


