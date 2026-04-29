# Captcha

The user needs to solve a captcha checkpoint.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**public_key** | **str** | The ID of the Company. | 
**data** | **str** | The ID of the Company. | 

## Example

```python
from unipile.models.captcha import Captcha

# TODO update the JSON string below
json = "{}"
# create an instance of Captcha from a JSON string
captcha_instance = Captcha.from_json(json)
# print the JSON string representation of the object
print(Captcha.to_json())

# convert the object into a dict
captcha_dict = captcha_instance.to_dict()
# create an instance of Captcha from a dict
captcha_from_dict = Captcha.from_dict(captcha_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


