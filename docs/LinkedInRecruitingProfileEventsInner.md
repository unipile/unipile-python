# LinkedInRecruitingProfileEventsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**last_updated_at** | **str** | The time at which the activity was updated. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**last_updated_by** | [**LinkedInProjectsInnerContributorsInner**](LinkedInProjectsInnerContributorsInner.md) |  | 
**event** | **str** | The type of event. | 
**message_content** | **str** | The text content of the message. | 
**message_status** | **str** | The current status of the message. | 
**note_content** | **str** | The text content of the note. | [optional] 
**link_content** | **str** | The URL of the link. | 
**project_id** | **str** | The ID of the project the user is related to. | 
**project_name** | **str** | The name of the project the user is related to. | 
**pipeline_stage** | **str** | The pipeline stage the user was added/moved to. | 

## Example

```python
from unipile.models.linked_in_recruiting_profile_events_inner import LinkedInRecruitingProfileEventsInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInRecruitingProfileEventsInner from a JSON string
linked_in_recruiting_profile_events_inner_instance = LinkedInRecruitingProfileEventsInner.from_json(json)
# print the JSON string representation of the object
print(LinkedInRecruitingProfileEventsInner.to_json())

# convert the object into a dict
linked_in_recruiting_profile_events_inner_dict = linked_in_recruiting_profile_events_inner_instance.to_dict()
# create an instance of LinkedInRecruitingProfileEventsInner from a dict
linked_in_recruiting_profile_events_inner_from_dict = LinkedInRecruitingProfileEventsInner.from_dict(linked_in_recruiting_profile_events_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


