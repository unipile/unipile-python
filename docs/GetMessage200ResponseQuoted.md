# GetMessage200ResponseQuoted

The quoted message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the message for the provider. | 
**text** | **str** | The text content of the message. | [optional] 
**attachments** | [**List[GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner]**](GetChatsList200ResponseDataInnerLastMessageAnyOf1QuotedAttachmentsInner.md) | List of message attachments. | 
**sender** | [**GetMessage200ResponseSender**](GetMessage200ResponseSender.md) |  | [optional] 

## Example

```python
from unipile.models.get_message200_response_quoted import GetMessage200ResponseQuoted

# TODO update the JSON string below
json = "{}"
# create an instance of GetMessage200ResponseQuoted from a JSON string
get_message200_response_quoted_instance = GetMessage200ResponseQuoted.from_json(json)
# print the JSON string representation of the object
print(GetMessage200ResponseQuoted.to_json())

# convert the object into a dict
get_message200_response_quoted_dict = get_message200_response_quoted_instance.to_dict()
# create an instance of GetMessage200ResponseQuoted from a dict
get_message200_response_quoted_from_dict = GetMessage200ResponseQuoted.from_dict(get_message200_response_quoted_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


