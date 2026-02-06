# OauthURL

For Oauth providers (Outlook, Google)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**url** | **str** | The URL to redirect to start the oauth flow of the provider. | 

## Example

```python
from unipile.models.oauth_url import OauthURL

# TODO update the JSON string below
json = "{}"
# create an instance of OauthURL from a JSON string
oauth_url_instance = OauthURL.from_json(json)
# print the JSON string representation of the object
print(OauthURL.to_json())

# convert the object into a dict
oauth_url_dict = oauth_url_instance.to_dict()
# create an instance of OauthURL from a dict
oauth_url_from_dict = OauthURL.from_dict(oauth_url_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


