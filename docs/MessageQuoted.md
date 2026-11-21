# MessageQuoted

The quoted message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the message for the provider. | 
**text** | **str** | The text content of the message. | [optional] 
**specifics** | **object** |  | [optional] 
**attachments** | [**List[MessageQuotedAttachmentsInner]**](MessageQuotedAttachmentsInner.md) | List of message attachments. | 
**sender** | [**MessageSender**](MessageSender.md) |  | [optional] 

## Example

```python
from unipile.models.message_quoted import MessageQuoted

# TODO update the JSON string below
json = "{}"
# create an instance of MessageQuoted from a JSON string
message_quoted_instance = MessageQuoted.from_json(json)
# print the JSON string representation of the object
print(MessageQuoted.to_json())

# convert the object into a dict
message_quoted_dict = message_quoted_instance.to_dict()
# create an instance of MessageQuoted from a dict
message_quoted_from_dict = MessageQuoted.from_dict(message_quoted_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


