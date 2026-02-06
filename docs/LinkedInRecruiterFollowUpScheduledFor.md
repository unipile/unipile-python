# LinkedInRecruiterFollowUpScheduledFor

The time frame within which to send the message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**days** | **float** | Days from now to send the message. | 
**timezone** | **str** | The time zone from which the message is scheduled (e.g. &#39;Europe/Paris&#39;, &#39;America/Phoenix&#39;...). | [optional] [default to 'Your browser time zone.']
**weeks** | **float** | Weeks from now to send the message. | 

## Example

```python
from unipile.models.linked_in_recruiter_follow_up_scheduled_for import LinkedInRecruiterFollowUpScheduledFor

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInRecruiterFollowUpScheduledFor from a JSON string
linked_in_recruiter_follow_up_scheduled_for_instance = LinkedInRecruiterFollowUpScheduledFor.from_json(json)
# print the JSON string representation of the object
print(LinkedInRecruiterFollowUpScheduledFor.to_json())

# convert the object into a dict
linked_in_recruiter_follow_up_scheduled_for_dict = linked_in_recruiter_follow_up_scheduled_for_instance.to_dict()
# create an instance of LinkedInRecruiterFollowUpScheduledFor from a dict
linked_in_recruiter_follow_up_scheduled_for_from_dict = LinkedInRecruiterFollowUpScheduledFor.from_dict(linked_in_recruiter_follow_up_scheduled_for_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


