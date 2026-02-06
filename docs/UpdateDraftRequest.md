# UpdateDraftRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**html** | **str** | The HTML content of the draft. Required for tracking. | [optional] 
**plain_text** | **str** | The plain text content of the draft. | [optional] 
**subject** | **str** | Subject of the draft. | [optional] 
**var_from** | [**GetEmailsList200ResponseDataInnerFromInner**](GetEmailsList200ResponseDataInnerFromInner.md) |  | [optional] 
**to** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | List of attendees to set in &#x60;to&#x60; header. | [optional] 
**cc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | List of attendees to set in &#x60;cc&#x60; header. | [optional] 
**bcc** | [**List[GetEmailsList200ResponseDataInnerFromInner]**](GetEmailsList200ResponseDataInnerFromInner.md) | List of attendees to set in &#x60;bcc&#x60; header. | [optional] 
**attachments** | [**List[SendEmailRequestAttachmentsInner]**](SendEmailRequestAttachmentsInner.md) | The list of file attachments to the draft. Any attachment already existing will be removed and replaced by the new ones. | [optional] 
**tracking_options** | [**SendEmailRequestTrackingOptions**](SendEmailRequestTrackingOptions.md) |  | [optional] 

## Example

```python
from unipile.models.update_draft_request import UpdateDraftRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateDraftRequest from a JSON string
update_draft_request_instance = UpdateDraftRequest.from_json(json)
# print the JSON string representation of the object
print(UpdateDraftRequest.to_json())

# convert the object into a dict
update_draft_request_dict = update_draft_request_instance.to_dict()
# create an instance of UpdateDraftRequest from a dict
update_draft_request_from_dict = UpdateDraftRequest.from_dict(update_draft_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


