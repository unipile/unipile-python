# WhatsApp4

Start the authentication intent with WhatsApp provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**credentials** | [**WhatsApp4Credentials**](WhatsApp4Credentials.md) |  | 
**config** | [**WhatsApp4Config**](WhatsApp4Config.md) |  | [optional] 

## Example

```python
from unipile.models.whats_app4 import WhatsApp4

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsApp4 from a JSON string
whats_app4_instance = WhatsApp4.from_json(json)
# print the JSON string representation of the object
print(WhatsApp4.to_json())

# convert the object into a dict
whats_app4_dict = whats_app4_instance.to_dict()
# create an instance of WhatsApp4 from a dict
whats_app4_from_dict = WhatsApp4.from_dict(whats_app4_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


