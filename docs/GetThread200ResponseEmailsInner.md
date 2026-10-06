# GetThread200ResponseEmailsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the email. | 
**message_id** | **str** | The Message-ID header value of the email. Use &#x60;id&#x60; in Unipile requests. | 
**thread_id** | **str** | The thread identifier. For IMAP, Unipile uses the server-provided thread ID when available. Otherwise, it uses the entire References header, or In-Reply-To, or Message-ID, in that order. A header-derived value may differ between messages in the same conversation and may be absent when none of these headers exists. | [optional] 
**body** | **str** | The complete body of the email: HTML when available, otherwise plain text. An empty string when the email has no body or meta_only&#x3D;true. | 
**body_plain** | **str** | The complete plain-text body of the email. Uses the original plain-text version when available, otherwise text converted from HTML. For Outlook, text is converted from the HTML body returned by Microsoft Graph, or taken directly from its plain-text body. An empty string when the email has no body or meta_only&#x3D;true. | 
**snippet** | **str** | A short preview of the email, not its complete plain-text body. Use body_plain for the full text. | 
**subject** | **str** | The subject of the email. | 
**headers** | [**List[GetEmailsList200ResponseDataInnerHeadersInner]**](GetEmailsList200ResponseDataInnerHeadersInner.md) | List of headers. A single email can sometimes have multiple headers with the same key name. Unipile adds all of the headers to the headers array without merging or de-duplicating the data. When the headers contain encoded data, Unipile adds it to the headers array without decoding it. | 
**var_from** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email was sent from. | [optional] 
**to** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email was sent to. | [optional] 
**cc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email was CC&#39;d to. An empty array when none are available. | 
**bcc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email was BCC&#39;d to. An empty array when none are available. | 
**reply_to** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the replies should be sent to. An empty array when none are available. | 
**var_date** | **str** | The date the email was sent. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**attachments** | [**List[GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner]**](GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner.md) | The attachments of the email. | 
**folders** | **List[str]** | The IDs of folders the email is in. For Gmail, the IDs of labels assigned to the email, excluding the UNREAD system label, which is exposed through is_unread instead. | 
**categories** | **List[str]** | List of categories assigned to the email. | [optional] 
**is_unread** | **bool** | Is the email unread. For Gmail, this reflects the UNREAD system label. | 

## Example

```python
from unipile.models.get_thread200_response_emails_inner import GetThread200ResponseEmailsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetThread200ResponseEmailsInner from a JSON string
get_thread200_response_emails_inner_instance = GetThread200ResponseEmailsInner.from_json(json)
# print the JSON string representation of the object
print(GetThread200ResponseEmailsInner.to_json())

# convert the object into a dict
get_thread200_response_emails_inner_dict = get_thread200_response_emails_inner_instance.to_dict()
# create an instance of GetThread200ResponseEmailsInner from a dict
get_thread200_response_emails_inner_from_dict = GetThread200ResponseEmailsInner.from_dict(get_thread200_response_emails_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


