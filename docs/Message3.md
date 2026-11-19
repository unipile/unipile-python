# Message3


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**last_updated_at** | **str** | The time at which the activity was updated. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**last_updated_by** | [**LinkedIn2InterestsTopVoicesInner**](LinkedIn2InterestsTopVoicesInner.md) |  | 
**event** | **str** | The type of event. | 
**message_content** | **str** | The text content of the message, when available. | 
**message_status** | **str** | The current status of the message. | 

## Example

```python
from unipile.models.message3 import Message3

# TODO update the JSON string below
json = "{}"
# create an instance of Message3 from a JSON string
message3_instance = Message3.from_json(json)
# print the JSON string representation of the object
print(Message3.to_json())

# convert the object into a dict
message3_dict = message3_instance.to_dict()
# create an instance of Message3 from a dict
message3_from_dict = Message3.from_dict(message3_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


