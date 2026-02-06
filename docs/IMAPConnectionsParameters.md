# IMAPConnectionsParameters


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user** | **str** | Username | 
**password** | **str** | Password | 
**host** | **str** | Server url/ip | 
**encryption** | **str** | The encryption method to use for the connection.               - &#x60;tls&#x60; will use the TLS encryption method.               - &#x60;ssl&#x60; will use the SSL encryption method.               - &#x60;starttls&#x60; will use the STARTTLS encryption method.               - &#x60;default&#x60; will use the default encryption method for the server. | [optional] [default to 'default']
**port** | **float** | Server port | 

## Example

```python
from unipile.models.imap_connections_parameters import IMAPConnectionsParameters

# TODO update the JSON string below
json = "{}"
# create an instance of IMAPConnectionsParameters from a JSON string
imap_connections_parameters_instance = IMAPConnectionsParameters.from_json(json)
# print the JSON string representation of the object
print(IMAPConnectionsParameters.to_json())

# convert the object into a dict
imap_connections_parameters_dict = imap_connections_parameters_instance.to_dict()
# create an instance of IMAPConnectionsParameters from a dict
imap_connections_parameters_from_dict = IMAPConnectionsParameters.from_dict(imap_connections_parameters_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


