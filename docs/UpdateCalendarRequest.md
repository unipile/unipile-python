# UpdateCalendarRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the new calendar | [optional] 
**description** | **str** | Description of the calendar | [optional] 
**background_color** | **str** | Background color of the calendar in hexadecimal format. | [optional] 

## Example

```python
from unipile.models.update_calendar_request import UpdateCalendarRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCalendarRequest from a JSON string
update_calendar_request_instance = UpdateCalendarRequest.from_json(json)
# print the JSON string representation of the object
print(UpdateCalendarRequest.to_json())

# convert the object into a dict
update_calendar_request_dict = update_calendar_request_instance.to_dict()
# create an instance of UpdateCalendarRequest from a dict
update_calendar_request_from_dict = UpdateCalendarRequest.from_dict(update_calendar_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


