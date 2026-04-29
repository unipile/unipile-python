# BasicAuthentication2

Use username and password to authenticate with Instagram.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | The username of the Instagram account. | 
**password** | **str** | The password of the Instagram account. | 

## Example

```python
from unipile.models.basic_authentication2 import BasicAuthentication2

# TODO update the JSON string below
json = "{}"
# create an instance of BasicAuthentication2 from a JSON string
basic_authentication2_instance = BasicAuthentication2.from_json(json)
# print the JSON string representation of the object
print(BasicAuthentication2.to_json())

# convert the object into a dict
basic_authentication2_dict = basic_authentication2_instance.to_dict()
# create an instance of BasicAuthentication2 from a dict
basic_authentication2_from_dict = BasicAuthentication2.from_dict(basic_authentication2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


