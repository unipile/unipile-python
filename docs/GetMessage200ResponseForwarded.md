# GetMessage200ResponseForwarded

Contains the original message if this message was forwarded from another chat, depending on provider support.     Some providers preserve the original sender and content, treating it as if it were sent by the account owner.     Others wrap the forwarded message within a new message (similar to a quote or attachment), in which case the original message appears here.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | The text content of the message. | [optional] 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | List of message attachments. | 
**object** | **str** |  | 
**sender** | [**GetMessage200ResponseSender**](GetMessage200ResponseSender.md) |  | [optional] 

## Example

```python
from unipile.models.get_message200_response_forwarded import GetMessage200ResponseForwarded

# TODO update the JSON string below
json = "{}"
# create an instance of GetMessage200ResponseForwarded from a JSON string
get_message200_response_forwarded_instance = GetMessage200ResponseForwarded.from_json(json)
# print the JSON string representation of the object
print(GetMessage200ResponseForwarded.to_json())

# convert the object into a dict
get_message200_response_forwarded_dict = get_message200_response_forwarded_instance.to_dict()
# create an instance of GetMessage200ResponseForwarded from a dict
get_message200_response_forwarded_from_dict = GetMessage200ResponseForwarded.from_dict(get_message200_response_forwarded_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


