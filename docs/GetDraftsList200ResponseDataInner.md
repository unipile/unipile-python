# GetDraftsList200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the draft. | 
**thread_id** | **str** | The ID of the thread the draft belongs to. | [optional] 
**body** | **str** | The body of the draft. | 
**snippet** | **str** | The snippet (preview) of the draft. | 
**subject** | **str** | The subject of the draft. | 
**var_from** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email should be sent from. | [optional] 
**to** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email should be sent to. | [optional] 
**cc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email should be CC&#39;d to. | [optional] 
**bcc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the email should be BCC&#39;d to. | [optional] 
**reply_to** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | The list of attendees that the replies should be sent to. | [optional] 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | The attachments of the draft. | 
**folders** | **List[Optional[str]]** | The folder the draft is in. For Gmail, the labels assigned to the draft. | 

## Example

```python
from unipile.models.get_drafts_list200_response_data_inner import GetDraftsList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetDraftsList200ResponseDataInner from a JSON string
get_drafts_list200_response_data_inner_instance = GetDraftsList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetDraftsList200ResponseDataInner.to_json())

# convert the object into a dict
get_drafts_list200_response_data_inner_dict = get_drafts_list200_response_data_inner_instance.to_dict()
# create an instance of GetDraftsList200ResponseDataInner from a dict
get_drafts_list200_response_data_inner_from_dict = GetDraftsList200ResponseDataInner.from_dict(get_drafts_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


