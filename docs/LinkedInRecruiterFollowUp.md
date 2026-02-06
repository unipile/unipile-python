# LinkedInRecruiterFollowUp

A follow-up message to be scheduled (Recruiter Pro contracts only).

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**subject** | **str** | The subject of the message. | 
**text** | **str** | The textual content of the message. | 
**attachments** | [**List[MessageFile]**](MessageFile.md) | The list of file attachments to the message to be sent in the chat. | [optional] 
**scheduled_for** | [**LinkedInRecruiterFollowUpScheduledFor**](LinkedInRecruiterFollowUpScheduledFor.md) |  | 

## Example

```python
from unipile.models.linked_in_recruiter_follow_up import LinkedInRecruiterFollowUp

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInRecruiterFollowUp from a JSON string
linked_in_recruiter_follow_up_instance = LinkedInRecruiterFollowUp.from_json(json)
# print the JSON string representation of the object
print(LinkedInRecruiterFollowUp.to_json())

# convert the object into a dict
linked_in_recruiter_follow_up_dict = linked_in_recruiter_follow_up_instance.to_dict()
# create an instance of LinkedInRecruiterFollowUp from a dict
linked_in_recruiter_follow_up_from_dict = LinkedInRecruiterFollowUp.from_dict(linked_in_recruiter_follow_up_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


