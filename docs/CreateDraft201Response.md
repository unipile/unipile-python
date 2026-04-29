# CreateDraft201Response


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
**folders** | **List[str]** | The folder the draft is in. For Gmail, the labels assigned to the draft. | 
**categories** | **List[str]** | List of categories assigned to the draft. | [optional] 

## Example

```python
from unipile.models.create_draft201_response import CreateDraft201Response

# TODO update the JSON string below
json = "{}"
# create an instance of CreateDraft201Response from a JSON string
create_draft201_response_instance = CreateDraft201Response.from_json(json)
# print the JSON string representation of the object
print(CreateDraft201Response.to_json())

# convert the object into a dict
create_draft201_response_dict = create_draft201_response_instance.to_dict()
# create an instance of CreateDraft201Response from a dict
create_draft201_response_from_dict = CreateDraft201Response.from_dict(create_draft201_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


