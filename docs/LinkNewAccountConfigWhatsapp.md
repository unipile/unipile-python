# LinkNewAccountConfigWhatsapp

WhatsApp specific configuration.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**custom_proxy** | [**CustomProxy1**](CustomProxy1.md) |  | [optional] 
**auto_proxy_config** | [**AutomaticProxyConfiguration**](AutomaticProxyConfiguration.md) |  | [optional] 
**allow_methods** | **List[str]** | The authentication methods to show in the hosted auth.             &#x60;qr&#x60; : QR Code Authentication             &#x60;pairing&#x60; : Pairing Code Authentication            | [optional] [default to ["qr","pairing"]]

## Example

```python
from unipile.models.link_new_account_config_whatsapp import LinkNewAccountConfigWhatsapp

# TODO update the JSON string below
json = "{}"
# create an instance of LinkNewAccountConfigWhatsapp from a JSON string
link_new_account_config_whatsapp_instance = LinkNewAccountConfigWhatsapp.from_json(json)
# print the JSON string representation of the object
print(LinkNewAccountConfigWhatsapp.to_json())

# convert the object into a dict
link_new_account_config_whatsapp_dict = link_new_account_config_whatsapp_instance.to_dict()
# create an instance of LinkNewAccountConfigWhatsapp from a dict
link_new_account_config_whatsapp_from_dict = LinkNewAccountConfigWhatsapp.from_dict(link_new_account_config_whatsapp_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


