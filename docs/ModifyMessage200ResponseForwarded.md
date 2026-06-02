# ModifyMessage200ResponseForwarded

Contains the original message if this message was forwarded from another chat, depending on provider support.     Some providers preserve the original sender and content, treating it as if it were sent by the account owner.     Others wrap the forwarded message within a new message (similar to a quote or attachment), in which case the original message appears here.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | The text content of the message. | [optional] 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | List of message attachments. | 
**sender** | [**ModifyMessage200ResponseSender**](ModifyMessage200ResponseSender.md) |  | [optional] 
**object** | **str** |  | 

## Example

```python
from unipile.models.modify_message200_response_forwarded import ModifyMessage200ResponseForwarded

# TODO update the JSON string below
json = "{}"
# create an instance of ModifyMessage200ResponseForwarded from a JSON string
modify_message200_response_forwarded_instance = ModifyMessage200ResponseForwarded.from_json(json)
# print the JSON string representation of the object
print(ModifyMessage200ResponseForwarded.to_json())

# convert the object into a dict
modify_message200_response_forwarded_dict = modify_message200_response_forwarded_instance.to_dict()
# create an instance of ModifyMessage200ResponseForwarded from a dict
modify_message200_response_forwarded_from_dict = ModifyMessage200ResponseForwarded.from_dict(modify_message200_response_forwarded_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


