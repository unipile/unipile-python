# Instagram

Start the authentication intent with Instagram provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**credentials** | [**InstagramCredentials**](InstagramCredentials.md) |  | 
**config** | [**InstagramConfig**](InstagramConfig.md) |  | [optional] 

## Example

```python
from unipile.models.instagram import Instagram

# TODO update the JSON string below
json = "{}"
# create an instance of Instagram from a JSON string
instagram_instance = Instagram.from_json(json)
# print the JSON string representation of the object
print(Instagram.to_json())

# convert the object into a dict
instagram_dict = instagram_instance.to_dict()
# create an instance of Instagram from a dict
instagram_from_dict = Instagram.from_dict(instagram_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


