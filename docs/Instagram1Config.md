# Instagram1Config

Instagram specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 
**allow_methods** | **List[str]** | The authentication methods to show in the hosted auth.           &#x60;credentials&#x60; : Credentials Authentication           &#x60;cookies&#x60; : Cookies Authentication          | [optional] [default to ["credentials"]]

## Example

```python
from unipile.models.instagram1_config import Instagram1Config

# TODO update the JSON string below
json = "{}"
# create an instance of Instagram1Config from a JSON string
instagram1_config_instance = Instagram1Config.from_json(json)
# print the JSON string representation of the object
print(Instagram1Config.to_json())

# convert the object into a dict
instagram1_config_dict = instagram1_config_instance.to_dict()
# create an instance of Instagram1Config from a dict
instagram1_config_from_dict = Instagram1Config.from_dict(instagram1_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


