# LinkedIn2Config

LinkedIn specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 
**products** | [**LinkedIn2ConfigProducts**](LinkedIn2ConfigProducts.md) |  | [optional] 

## Example

```python
from unipile.models.linked_in2_config import LinkedIn2Config

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn2Config from a JSON string
linked_in2_config_instance = LinkedIn2Config.from_json(json)
# print the JSON string representation of the object
print(LinkedIn2Config.to_json())

# convert the object into a dict
linked_in2_config_dict = linked_in2_config_instance.to_dict()
# create an instance of LinkedIn2Config from a dict
linked_in2_config_from_dict = LinkedIn2Config.from_dict(linked_in2_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


