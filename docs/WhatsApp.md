# WhatsApp

Start the authentication intent with WhatsApp provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**credentials** | [**WhatsAppCredentials**](WhatsAppCredentials.md) |  | 
**config** | [**WhatsAppConfig**](WhatsAppConfig.md) |  | [optional] 

## Example

```python
from unipile.models.whats_app import WhatsApp

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsApp from a JSON string
whats_app_instance = WhatsApp.from_json(json)
# print the JSON string representation of the object
print(WhatsApp.to_json())

# convert the object into a dict
whats_app_dict = whats_app_instance.to_dict()
# create an instance of WhatsApp from a dict
whats_app_from_dict = WhatsApp.from_dict(whats_app_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


