# ReAuthenticateExistingAccount

Generate a link to re-authenticate an existing account with Unipile.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**expires_on** | **datetime** | The expiration date of the link. Use ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**redirect_uri** | **str** | The URL to redirect to after the authentication process. If the authentication succeeded, &#x60;account_id&#x60; and &#x60;provider&#x60; will be present in query params, along the specified &#x60;state&#x60;. If the authentication has failed, &#x60;error_title&#x60; is present instead. This is useful for your app to be aware of the authentication result and to redirect the user to the correct page of your app. | 
**state** | **str** | State data sent as query parameter in the redirect_uri and in the &#x60;account.add&#x60; / &#x60;account.reconnect&#x60; webhook payload after the authentication process. | [optional] 
**config** | [**LinkNewAccountConfig**](LinkNewAccountConfig.md) |  | [optional] 
**account_id** | **str** | Required to re-authenticate an existing account. The ID of the Account to re-authenticate. | 

## Example

```python
from unipile.models.re_authenticate_existing_account import ReAuthenticateExistingAccount

# TODO update the JSON string below
json = "{}"
# create an instance of ReAuthenticateExistingAccount from a JSON string
re_authenticate_existing_account_instance = ReAuthenticateExistingAccount.from_json(json)
# print the JSON string representation of the object
print(ReAuthenticateExistingAccount.to_json())

# convert the object into a dict
re_authenticate_existing_account_dict = re_authenticate_existing_account_instance.to_dict()
# create an instance of ReAuthenticateExistingAccount from a dict
re_authenticate_existing_account_from_dict = ReAuthenticateExistingAccount.from_dict(re_authenticate_existing_account_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


