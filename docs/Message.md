# Message


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**last_updated_at** | **str** | The time at which the activity was updated. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**last_updated_by** | [**LinkedInProjectsInnerContributorsInner**](LinkedInProjectsInnerContributorsInner.md) |  | 
**event** | **str** | The type of event. | 
**message_content** | **str** | The text content of the message. | 
**message_status** | **str** | The current status of the message. | 

## Example

```python
from unipile.models.message import Message

# TODO update the JSON string below
json = "{}"
# create an instance of Message from a JSON string
message_instance = Message.from_json(json)
# print the JSON string representation of the object
print(Message.to_json())

# convert the object into a dict
message_dict = message_instance.to_dict()
# create an instance of Message from a dict
message_from_dict = Message.from_dict(message_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


