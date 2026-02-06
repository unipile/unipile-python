# GetMessagesList200ResponseDataInnerForwarded

Contains the original message if this message was forwarded from another chat, depending on provider support.     Some providers preserve the original sender and content, treating it as if it were sent by the account owner.     Others wrap the forwarded message within a new message (similar to a quote or attachment), in which case the original message appears here.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | The text content of the message. | [optional] 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | List of message attachments. | 
**sender** | [**GetMessagesList200ResponseDataInnerSender**](GetMessagesList200ResponseDataInnerSender.md) |  | [optional] 
**object** | **str** |  | 

## Example

```python
from unipile.models.get_messages_list200_response_data_inner_forwarded import GetMessagesList200ResponseDataInnerForwarded

# TODO update the JSON string below
json = "{}"
# create an instance of GetMessagesList200ResponseDataInnerForwarded from a JSON string
get_messages_list200_response_data_inner_forwarded_instance = GetMessagesList200ResponseDataInnerForwarded.from_json(json)
# print the JSON string representation of the object
print(GetMessagesList200ResponseDataInnerForwarded.to_json())

# convert the object into a dict
get_messages_list200_response_data_inner_forwarded_dict = get_messages_list200_response_data_inner_forwarded_instance.to_dict()
# create an instance of GetMessagesList200ResponseDataInnerForwarded from a dict
get_messages_list200_response_data_inner_forwarded_from_dict = GetMessagesList200ResponseDataInnerForwarded.from_dict(get_messages_list200_response_data_inner_forwarded_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


