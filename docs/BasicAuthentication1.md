# BasicAuthentication1

Use email and password to authenticate with LinkedIn.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | Email or phone of the LinkedIn account. | 
**password** | **str** | Password of the LinkedIn account. | 

## Example

```python
from unipile.models.basic_authentication1 import BasicAuthentication1

# TODO update the JSON string below
json = "{}"
# create an instance of BasicAuthentication1 from a JSON string
basic_authentication1_instance = BasicAuthentication1.from_json(json)
# print the JSON string representation of the object
print(BasicAuthentication1.to_json())

# convert the object into a dict
basic_authentication1_dict = basic_authentication1_instance.to_dict()
# create an instance of BasicAuthentication1 from a dict
basic_authentication1_from_dict = BasicAuthentication1.from_dict(basic_authentication1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


