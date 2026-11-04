# ModifyMessageRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | The new textual content of the message. It&#39;s recommended not to use HTML or Markdown. To mention a chat participant, write &#x60;@&#x60; followed by their user ID, as found in &#x60;sender_id&#x60; or the chat attendees: it is replaced with their name and notifies them where the provider supports mentions. A provider may still deliver the mention as plain text. | 

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


