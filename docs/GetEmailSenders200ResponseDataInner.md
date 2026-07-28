# GetEmailSenders200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | Object type identifier, always \&quot;EmailSender\&quot;. | 
**email** | **str** | Email address that can be placed in the &#x60;from&#x60; header when sending emails. | 
**display_name** | **str** | Display name associated with the address, when the provider exposes one. | [optional] 
**is_primary** | **bool** | Whether this is the primary address of the mailbox (the address used to authenticate the account). | 
**is_default** | **bool** | Whether this is the default \&quot;From:\&quot; address used when composing a new message. Only exposed by providers that have a distinct default sender (Gmail). | [optional] 
**verification_status** | **str** | Readiness of the address for sending. &#x60;verified&#x60;: the address is confirmed and can be used in the &#x60;from&#x60; field. &#x60;pending&#x60;: the email sender exists but has not completed verification and is not ready to send (Gmail custom addresses). &#x60;unknown&#x60;: the provider does not expose per-address readiness (e.g. Outlook proxy addresses, whose usability depends on the tenant &#x60;SendFromAliasEnabled&#x60; setting). | 

## Example

```python
from unipile.models.get_email_senders200_response_data_inner import GetEmailSenders200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetEmailSenders200ResponseDataInner from a JSON string
get_email_senders200_response_data_inner_instance = GetEmailSenders200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetEmailSenders200ResponseDataInner.to_json())

# convert the object into a dict
get_email_senders200_response_data_inner_dict = get_email_senders200_response_data_inner_instance.to_dict()
# create an instance of GetEmailSenders200ResponseDataInner from a dict
get_email_senders200_response_data_inner_from_dict = GetEmailSenders200ResponseDataInner.from_dict(get_email_senders200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


