# FacebookCredentials

The user credentials required by the provider to authenticate with.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | Email or username of the Facebook account. | 
**password** | **str** | Password of the Facebook account. | 
**xs** | **str** | The &#x60;xs&#x60; cookie value. | 
**c_user** | **str** | The &#x60;c_user&#x60; cookie value. | 
**datr** | **str** | The &#x60;datr&#x60; cookie value. | 
**sb** | **str** | Optional &#x60;sb&#x60; cookie value. | [optional] 
**fr** | **str** | Optional &#x60;fr&#x60; cookie value. | [optional] 
**wd** | **str** | Optional &#x60;wd&#x60; cookie value. | [optional] 
**presence** | **str** | Optional &#x60;presence&#x60; cookie value. | [optional] 
**oo** | **str** | Optional &#x60;oo&#x60; cookie value. | [optional] 

## Example

```python
from unipile.models.facebook_credentials import FacebookCredentials

# TODO update the JSON string below
json = "{}"
# create an instance of FacebookCredentials from a JSON string
facebook_credentials_instance = FacebookCredentials.from_json(json)
# print the JSON string representation of the object
print(FacebookCredentials.to_json())

# convert the object into a dict
facebook_credentials_dict = facebook_credentials_instance.to_dict()
# create an instance of FacebookCredentials from a dict
facebook_credentials_from_dict = FacebookCredentials.from_dict(facebook_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


