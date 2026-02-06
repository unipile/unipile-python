# GetMessagesList200ResponseDataInnerQuoted

The quoted message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The unique identifier of the message for the provider. | 
**text** | **str** | The text content of the message. | [optional] 
**attachments** | [**List[GetMessagesList200ResponseDataInnerQuotedAttachmentsInner]**](GetMessagesList200ResponseDataInnerQuotedAttachmentsInner.md) | List of message attachments. | 
**sender** | [**GetMessagesList200ResponseDataInnerSender**](GetMessagesList200ResponseDataInnerSender.md) |  | [optional] 

## Example

```python
from unipile.models.get_messages_list200_response_data_inner_quoted import GetMessagesList200ResponseDataInnerQuoted

# TODO update the JSON string below
json = "{}"
# create an instance of GetMessagesList200ResponseDataInnerQuoted from a JSON string
get_messages_list200_response_data_inner_quoted_instance = GetMessagesList200ResponseDataInnerQuoted.from_json(json)
# print the JSON string representation of the object
print(GetMessagesList200ResponseDataInnerQuoted.to_json())

# convert the object into a dict
get_messages_list200_response_data_inner_quoted_dict = get_messages_list200_response_data_inner_quoted_instance.to_dict()
# create an instance of GetMessagesList200ResponseDataInnerQuoted from a dict
get_messages_list200_response_data_inner_quoted_from_dict = GetMessagesList200ResponseDataInnerQuoted.from_dict(get_messages_list200_response_data_inner_quoted_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


