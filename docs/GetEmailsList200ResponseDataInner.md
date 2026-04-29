# GetEmailsList200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the email. | 
**message_id** | **str** | The Message-ID header value of the email. Use &#x60;id&#x60; in Unipile requests. | 
**thread_id** | **str** | The ID of the thread the email belongs to. | [optional] 
**body** | **str** | The body of the email. | 
**snippet** | **str** | The snippet (preview) of the email. | 
**subject** | **str** | The subject of the email. | 
**headers** | [**List[GetEmailsList200ResponseDataInnerHeadersInner]**](GetEmailsList200ResponseDataInnerHeadersInner.md) | List of headers. A single email can sometimes have multiple headers with the same key name. Unipile adds all of the headers to the headers array without merging or de-duplicating the data. When the headers contain encoded data, Unipile adds it to the headers array without decoding it. | 
**var_from** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email was sent from. | [optional] 
**to** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email was sent to. | [optional] 
**cc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email was CC&#39;d to. | [optional] 
**bcc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email was BCC&#39;d to. | [optional] 
**reply_to** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the replies should be sent to. | [optional] 
**var_date** | **str** | The date the email was sent. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | The attachments of the email. | 
**folders** | **List[Optional[str]]** | The IDs of folders the email is in. For Gmail, the IDs of labels assigned to the email. | 
**categories** | **List[str]** | List of categories assigned to the email. | [optional] 
**is_unread** | **bool** | Is the email unread. | 

## Example

```python
from unipile.models.get_emails_list200_response_data_inner import GetEmailsList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetEmailsList200ResponseDataInner from a JSON string
get_emails_list200_response_data_inner_instance = GetEmailsList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetEmailsList200ResponseDataInner.to_json())

# convert the object into a dict
get_emails_list200_response_data_inner_dict = get_emails_list200_response_data_inner_instance.to_dict()
# create an instance of GetEmailsList200ResponseDataInner from a dict
get_emails_list200_response_data_inner_from_dict = GetEmailsList200ResponseDataInner.from_dict(get_emails_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


