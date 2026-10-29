# CredentialsAuthentication

Use Facebook credentials to authenticate with Meta messaging.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | Email or username of the Facebook account. | 
**password** | **str** | Password of the Facebook account. | 

## Example

```python
from unipile.models.credentials_authentication import CredentialsAuthentication

# TODO update the JSON string below
json = "{}"
# create an instance of CredentialsAuthentication from a JSON string
credentials_authentication_instance = CredentialsAuthentication.from_json(json)
# print the JSON string representation of the object
print(CredentialsAuthentication.to_json())

# convert the object into a dict
credentials_authentication_dict = credentials_authentication_instance.to_dict()
# create an instance of CredentialsAuthentication from a dict
credentials_authentication_from_dict = CredentialsAuthentication.from_dict(credentials_authentication_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


