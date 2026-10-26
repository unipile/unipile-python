# Instagram2Credentials

The user credentials required by the provider to authenticate with.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | The username of the Instagram account. | 
**password** | **str** | The password of the Instagram account. | 
**sessionid** | **str** | The sessionid cookie value. | 

## Example

```python
from unipile.models.instagram2_credentials import Instagram2Credentials

# TODO update the JSON string below
json = "{}"
# create an instance of Instagram2Credentials from a JSON string
instagram2_credentials_instance = Instagram2Credentials.from_json(json)
# print the JSON string representation of the object
print(Instagram2Credentials.to_json())

# convert the object into a dict
instagram2_credentials_dict = instagram2_credentials_instance.to_dict()
# create an instance of Instagram2Credentials from a dict
instagram2_credentials_from_dict = Instagram2Credentials.from_dict(instagram2_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


