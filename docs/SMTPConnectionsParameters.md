# SMTPConnectionsParameters


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
from unipile.models.smtp_connections_parameters import SMTPConnectionsParameters

# TODO update the JSON string below
json = "{}"
# create an instance of SMTPConnectionsParameters from a JSON string
smtp_connections_parameters_instance = SMTPConnectionsParameters.from_json(json)
# print the JSON string representation of the object
print(SMTPConnectionsParameters.to_json())

# convert the object into a dict
smtp_connections_parameters_dict = smtp_connections_parameters_instance.to_dict()
# create an instance of SMTPConnectionsParameters from a dict
smtp_connections_parameters_from_dict = SMTPConnectionsParameters.from_dict(smtp_connections_parameters_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


