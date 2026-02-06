# IMAPCredentials


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user** | **str** | Username | 
**password** | **str** | Password | 
**imap** | [**IMAPConnectionsParameters**](IMAPConnectionsParameters.md) |  | 
**smtp** | [**SMTPConnectionsParameters**](SMTPConnectionsParameters.md) |  | 

## Example

```python
from unipile.models.imap_credentials import IMAPCredentials

# TODO update the JSON string below
json = "{}"
# create an instance of IMAPCredentials from a JSON string
imap_credentials_instance = IMAPCredentials.from_json(json)
# print the JSON string representation of the object
print(IMAPCredentials.to_json())

# convert the object into a dict
imap_credentials_dict = imap_credentials_instance.to_dict()
# create an instance of IMAPCredentials from a dict
imap_credentials_from_dict = IMAPCredentials.from_dict(imap_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


