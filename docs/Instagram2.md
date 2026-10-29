# Instagram2

Start the authentication intent with Instagram provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**credentials** | [**Instagram2Credentials**](Instagram2Credentials.md) |  | 
**config** | [**Instagram2Config**](Instagram2Config.md) |  | [optional] 

## Example

```python
from unipile.models.instagram2 import Instagram2

# TODO update the JSON string below
json = "{}"
# create an instance of Instagram2 from a JSON string
instagram2_instance = Instagram2.from_json(json)
# print the JSON string representation of the object
print(Instagram2.to_json())

# convert the object into a dict
instagram2_dict = instagram2_instance.to_dict()
# create an instance of Instagram2 from a dict
instagram2_from_dict = Instagram2.from_dict(instagram2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


