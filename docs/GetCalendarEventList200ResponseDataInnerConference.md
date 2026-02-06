# GetCalendarEventList200ResponseDataInnerConference


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The conference provider.         - &#x60;google_meet&#x60; is a Google Meet conference.         - &#x60;zoom&#x60; is a Zoom conference.         - &#x60;skype&#x60; is a Skype conference.         - &#x60;teams&#x60; is a Microsoft Teams conference.         - &#x60;unknown&#x60; is an unknown conference provider. | 
**url** | **str** | The conference URL. | 

## Example

```python
from unipile.models.get_calendar_event_list200_response_data_inner_conference import GetCalendarEventList200ResponseDataInnerConference

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarEventList200ResponseDataInnerConference from a JSON string
get_calendar_event_list200_response_data_inner_conference_instance = GetCalendarEventList200ResponseDataInnerConference.from_json(json)
# print the JSON string representation of the object
print(GetCalendarEventList200ResponseDataInnerConference.to_json())

# convert the object into a dict
get_calendar_event_list200_response_data_inner_conference_dict = get_calendar_event_list200_response_data_inner_conference_instance.to_dict()
# create an instance of GetCalendarEventList200ResponseDataInnerConference from a dict
get_calendar_event_list200_response_data_inner_conference_from_dict = GetCalendarEventList200ResponseDataInnerConference.from_dict(get_calendar_event_list200_response_data_inner_conference_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


