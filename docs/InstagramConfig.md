# InstagramConfig

Instagram specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 

## Example

```python
from unipile.models.instagram_config import InstagramConfig

# TODO update the JSON string below
json = "{}"
# create an instance of InstagramConfig from a JSON string
instagram_config_instance = InstagramConfig.from_json(json)
# print the JSON string representation of the object
print(InstagramConfig.to_json())

# convert the object into a dict
instagram_config_dict = instagram_config_instance.to_dict()
# create an instance of InstagramConfig from a dict
instagram_config_from_dict = InstagramConfig.from_dict(instagram_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


