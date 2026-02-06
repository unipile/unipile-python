# CreateDraftRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**html** | **str** | The HTML content of the draft. Required for tracking. | [optional] 
**plain_text** | **str** | The plain text content of the draft. | [optional] 
**subject** | **str** | Subject of the draft. | [optional] 
**var_from** | [**GetEmailsList200ResponseDataInnerFromInner**](GetEmailsList200ResponseDataInnerFromInner.md) |  | [optional] 
**to** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | List of attendees to set in &#x60;to&#x60; header. | 
**cc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | List of attendees to set in &#x60;cc&#x60; header. | [optional] 
**bcc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | List of attendees to set in &#x60;bcc&#x60; header. | [optional] 
**attachments** | [**List[SendEmailRequestAttachmentsInner]**](SendEmailRequestAttachmentsInner.md) | The list of file attachments to the draft. | [optional] 
**tracking_options** | [**SendEmailRequestTrackingOptions**](SendEmailRequestTrackingOptions.md) |  | [optional] 

## Example

```python
from unipile.models.create_draft_request import CreateDraftRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateDraftRequest from a JSON string
create_draft_request_instance = CreateDraftRequest.from_json(json)
# print the JSON string representation of the object
print(CreateDraftRequest.to_json())

# convert the object into a dict
create_draft_request_dict = create_draft_request_instance.to_dict()
# create an instance of CreateDraftRequest from a dict
create_draft_request_from_dict = CreateDraftRequest.from_dict(create_draft_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


