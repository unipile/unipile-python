# SendEmailRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**html** | **str** | The HTML content of the email. Required for tracking. | [optional] 
**plain_text** | **str** | The plain text content of the email. | [optional] 
**subject** | **str** | Subject of the email. | [optional] 
**var_from** | [**GetEmailsList200ResponseDataInnerFromInner**](GetEmailsList200ResponseDataInnerFromInner.md) |  | [optional] 
**to** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | List of attendees to set in &#x60;to&#x60; header. | 
**cc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | List of attendees to set in &#x60;cc&#x60; header. | [optional] 
**bcc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | List of attendees to set in &#x60;bcc&#x60; header. | [optional] 
**reply_to** | **str** | The ID of the email message that you&#39;re replying to. For Gmail and Outlook, this is the provider ID for the email message that you&#39;re replying to. For IMAP Send, this is the RFC822 Message-ID header of the email message that you&#39;re replying to. | [optional] 
**attachments** | [**List[SendEmailRequestAttachmentsInner]**](SendEmailRequestAttachmentsInner.md) | The list of file attachments to the email. | [optional] 
**custom_headers** | [**List[SendEmailRequestCustomHeadersInner]**](SendEmailRequestCustomHeadersInner.md) | An array of custom headers to add to the email. Each header overrides any existing header with the same name (case-insensitive), including headers set by other fields such as &#x60;to&#x60;, &#x60;cc&#x60;, &#x60;bcc&#x60;, &#x60;from&#x60;, &#x60;subject&#x60;, or &#x60;reply_to&#x60;. | [optional] 
**tracking_options** | [**SendEmailRequestTrackingOptions**](SendEmailRequestTrackingOptions.md) |  | [optional] 

## Example

```python
from unipile.models.send_email_request import SendEmailRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SendEmailRequest from a JSON string
send_email_request_instance = SendEmailRequest.from_json(json)
# print the JSON string representation of the object
print(SendEmailRequest.to_json())

# convert the object into a dict
send_email_request_dict = send_email_request_instance.to_dict()
# create an instance of SendEmailRequest from a dict
send_email_request_from_dict = SendEmailRequest.from_dict(send_email_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


