# LinkedInRecruiter

Specific options for a LinkedIn recruiter chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**subject** | **str** | The subject of the chat. | 
**signature** | **str** | The signature of the sender. | 
**visibility** | **str** | The level of visibility of the conversation within your organization. | [optional] [default to 'PRIVATE']
**intent** | **str** | The purpose of the chat. | [optional] [default to 'HIRE_FOR_CLIENT']
**send_as** | **str** | Whether you want to send the message via InMail or email using profile data. | [optional] [default to 'INMAIL']
**channel_type** | **str** | The channel from the hiring project talent pool from which to start the chat. | [optional] 
**follow_up** | [**LinkedInRecruiterFollowUp**](LinkedInRecruiterFollowUp.md) |  | [optional] 

## Example

```python
from unipile.models.linked_in_recruiter import LinkedInRecruiter

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInRecruiter from a JSON string
linked_in_recruiter_instance = LinkedInRecruiter.from_json(json)
# print the JSON string representation of the object
print(LinkedInRecruiter.to_json())

# convert the object into a dict
linked_in_recruiter_dict = linked_in_recruiter_instance.to_dict()
# create an instance of LinkedInRecruiter from a dict
linked_in_recruiter_from_dict = LinkedInRecruiter.from_dict(linked_in_recruiter_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


