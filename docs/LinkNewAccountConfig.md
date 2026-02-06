# LinkNewAccountConfig

Specific provider configuration for the hosted auth session.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**google** | [**LinkNewAccountConfigGoogle**](LinkNewAccountConfigGoogle.md) |  | [optional] 
**outlook** | [**LinkNewAccountConfigGoogle**](LinkNewAccountConfigGoogle.md) |  | [optional] 
**linkedin** | [**LinkNewAccountConfigLinkedin**](LinkNewAccountConfigLinkedin.md) |  | [optional] 
**whatsapp** | [**WhatsAppConfig**](WhatsAppConfig.md) |  | [optional] 
**instagram** | [**InstagramConfig**](InstagramConfig.md) |  | [optional] 
**imap** | [**LinkNewAccountConfigImap**](LinkNewAccountConfigImap.md) |  | [optional] 
**telegram** | [**TelegramConfig**](TelegramConfig.md) |  | [optional] 
**var_global** | [**LinkNewAccountConfigGlobal**](LinkNewAccountConfigGlobal.md) |  | [optional] 

## Example

```python
from unipile.models.link_new_account_config import LinkNewAccountConfig

# TODO update the JSON string below
json = "{}"
# create an instance of LinkNewAccountConfig from a JSON string
link_new_account_config_instance = LinkNewAccountConfig.from_json(json)
# print the JSON string representation of the object
print(LinkNewAccountConfig.to_json())

# convert the object into a dict
link_new_account_config_dict = link_new_account_config_instance.to_dict()
# create an instance of LinkNewAccountConfig from a dict
link_new_account_config_from_dict = LinkNewAccountConfig.from_dict(link_new_account_config_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


