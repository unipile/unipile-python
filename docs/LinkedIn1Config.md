# LinkedIn1Config

LinkedIn specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 
**products** | [**LinkedIn1ConfigProducts**](LinkedIn1ConfigProducts.md) |  | [optional] 

## Example

```python
from unipile.models.linked_in1_config import LinkedIn1Config

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1Config from a JSON string
linked_in1_config_instance = LinkedIn1Config.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1Config.to_json())

# convert the object into a dict
linked_in1_config_dict = linked_in1_config_instance.to_dict()
# create an instance of LinkedIn1Config from a dict
linked_in1_config_from_dict = LinkedIn1Config.from_dict(linked_in1_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


