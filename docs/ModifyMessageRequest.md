# ModifyMessageRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | The new textual content of the message. It&#39;s recommended not to use HTML or Markdown. | 

## Example

```python
from unipile.models.modify_message_request import ModifyMessageRequest

# TODO update the JSON string below
json = "{}"
# create an instance of ModifyMessageRequest from a JSON string
modify_message_request_instance = ModifyMessageRequest.from_json(json)
# print the JSON string representation of the object
print(ModifyMessageRequest.to_json())

# convert the object into a dict
modify_message_request_dict = modify_message_request_instance.to_dict()
# create an instance of ModifyMessageRequest from a dict
modify_message_request_from_dict = ModifyMessageRequest.from_dict(modify_message_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


