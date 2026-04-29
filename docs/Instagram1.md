# Instagram1

Start the authentication intent with Instagram provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**credentials** | [**Instagram1Credentials**](Instagram1Credentials.md) |  | 
**config** | [**Instagram1Config**](Instagram1Config.md) |  | [optional] 

## Example

```python
from unipile.models.instagram1 import Instagram1

# TODO update the JSON string below
json = "{}"
# create an instance of Instagram1 from a JSON string
instagram1_instance = Instagram1.from_json(json)
# print the JSON string representation of the object
print(Instagram1.to_json())

# convert the object into a dict
instagram1_dict = instagram1_instance.to_dict()
# create an instance of Instagram1 from a dict
instagram1_from_dict = Instagram1.from_dict(instagram1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


