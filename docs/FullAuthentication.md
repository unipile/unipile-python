# FullAuthentication

Full authentication, you can manually specify the IMAP/SMTP connection parameters. This is useful if the basic authentication method fails.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**imap** | [**IMAPConnectionsParameters**](IMAPConnectionsParameters.md) |  | 
**smtp** | [**SMTPConnectionsParameters**](SMTPConnectionsParameters.md) |  | 

## Example

```python
from unipile.models.full_authentication import FullAuthentication

# TODO update the JSON string below
json = "{}"
# create an instance of FullAuthentication from a JSON string
full_authentication_instance = FullAuthentication.from_json(json)
# print the JSON string representation of the object
print(FullAuthentication.to_json())

# convert the object into a dict
full_authentication_dict = full_authentication_instance.to_dict()
# create an instance of FullAuthentication from a dict
full_authentication_from_dict = FullAuthentication.from_dict(full_authentication_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


