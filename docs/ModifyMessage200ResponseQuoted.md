# ModifyMessage200ResponseQuoted

The quoted message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the message for the provider. | 
**text** | **str** | The text content of the message. | [optional] 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | List of message attachments. | 
**sender** | [**UpdateChat200ResponseParticipantsInnerUser**](UpdateChat200ResponseParticipantsInnerUser.md) |  | [optional] 

## Example

```python
from unipile.models.modify_message200_response_quoted import ModifyMessage200ResponseQuoted

# TODO update the JSON string below
json = "{}"
# create an instance of ModifyMessage200ResponseQuoted from a JSON string
modify_message200_response_quoted_instance = ModifyMessage200ResponseQuoted.from_json(json)
# print the JSON string representation of the object
print(ModifyMessage200ResponseQuoted.to_json())

# convert the object into a dict
modify_message200_response_quoted_dict = modify_message200_response_quoted_instance.to_dict()
# create an instance of ModifyMessage200ResponseQuoted from a dict
modify_message200_response_quoted_from_dict = ModifyMessage200ResponseQuoted.from_dict(modify_message200_response_quoted_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


