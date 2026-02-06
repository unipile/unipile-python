# BasicAuthentication

Basic authentication, our servers will try to guess the correct IMAP/SMTP connection parameters for your IMAP provider. If this fails, an error will be returned and you should use the full authentication method.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user** | **str** | Username | 
**password** | **str** | Password | 

## Example

```python
from unipile.models.basic_authentication import BasicAuthentication

# TODO update the JSON string below
json = "{}"
# create an instance of BasicAuthentication from a JSON string
basic_authentication_instance = BasicAuthentication.from_json(json)
# print the JSON string representation of the object
print(BasicAuthentication.to_json())

# convert the object into a dict
basic_authentication_dict = basic_authentication_instance.to_dict()
# create an instance of BasicAuthentication from a dict
basic_authentication_from_dict = BasicAuthentication.from_dict(basic_authentication_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


