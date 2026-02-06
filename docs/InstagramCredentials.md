# InstagramCredentials


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | The username of the Instagram account. | 
**password** | **str** | The password of the Instagram account. | 

## Example

```python
from unipile.models.instagram_credentials import InstagramCredentials

# TODO update the JSON string below
json = "{}"
# create an instance of InstagramCredentials from a JSON string
instagram_credentials_instance = InstagramCredentials.from_json(json)
# print the JSON string representation of the object
print(InstagramCredentials.to_json())

# convert the object into a dict
instagram_credentials_dict = instagram_credentials_instance.to_dict()
# create an instance of InstagramCredentials from a dict
instagram_credentials_from_dict = InstagramCredentials.from_dict(instagram_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


