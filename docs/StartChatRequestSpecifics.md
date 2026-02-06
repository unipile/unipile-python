# StartChatRequestSpecifics

Object containing provider-specific chat data.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**linkedin** | [**StartChatRequestSpecificsLinkedin**](StartChatRequestSpecificsLinkedin.md) |  | [optional] 

## Example

```python
from unipile.models.start_chat_request_specifics import StartChatRequestSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of StartChatRequestSpecifics from a JSON string
start_chat_request_specifics_instance = StartChatRequestSpecifics.from_json(json)
# print the JSON string representation of the object
print(StartChatRequestSpecifics.to_json())

# convert the object into a dict
start_chat_request_specifics_dict = start_chat_request_specifics_instance.to_dict()
# create an instance of StartChatRequestSpecifics from a dict
start_chat_request_specifics_from_dict = StartChatRequestSpecifics.from_dict(start_chat_request_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


