# MessageForwarded

Contains the original message if this message was forwarded from another chat, depending on provider support.     Some providers preserve the original sender and content, treating it as if it were sent by the account owner.     Others wrap the forwarded message within a new message (similar to a quote or attachment), in which case the original message appears here.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | The text content of the message. | [optional] 
**specifics** | **object** |  | [optional] 
**attachments** | [**List[MessageQuotedAttachmentsInner]**](MessageQuotedAttachmentsInner.md) | List of message attachments. | 
**sender** | [**MessageSender**](MessageSender.md) |  | [optional] 
**object** | **str** |  | 

## Example

```python
from unipile.models.message_forwarded import MessageForwarded

# TODO update the JSON string below
json = "{}"
# create an instance of MessageForwarded from a JSON string
message_forwarded_instance = MessageForwarded.from_json(json)
# print the JSON string representation of the object
print(MessageForwarded.to_json())

# convert the object into a dict
message_forwarded_dict = message_forwarded_instance.to_dict()
# create an instance of MessageForwarded from a dict
message_forwarded_from_dict = MessageForwarded.from_dict(message_forwarded_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


