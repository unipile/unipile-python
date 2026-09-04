# Telegram1

Start the authentication intent with Telegram provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**credentials** | [**Telegram1Credentials**](Telegram1Credentials.md) |  | 
**config** | [**Telegram1Config**](Telegram1Config.md) |  | [optional] 

## Example

```python
from unipile.models.telegram1 import Telegram1

# TODO update the JSON string below
json = "{}"
# create an instance of Telegram1 from a JSON string
telegram1_instance = Telegram1.from_json(json)
# print the JSON string representation of the object
print(Telegram1.to_json())

# convert the object into a dict
telegram1_dict = telegram1_instance.to_dict()
# create an instance of Telegram1 from a dict
telegram1_from_dict = Telegram1.from_dict(telegram1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


