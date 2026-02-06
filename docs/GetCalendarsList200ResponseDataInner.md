# GetCalendarsList200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the calendar. | 
**name** | **str** | Name of the calendar. | 
**description** | **str** | Description of the calendar. | [optional] 
**is_read_only** | **bool** | Indicates if the calendar is read-only or not. | 
**is_owned_by_user** | **bool** | Indicates if the user owns this calendar. | 
**is_default** | **bool** | Indicates if this is the primary calendar of the user. | 
**background_color** | **str** | Background color of the calendar in hexadecimal format. | 
**text_color** | **str** | Foreground color of the calendar in hexadecimal format. | [optional] 
**timezone** | **str** | Timezone used in this calendar. | [optional] 

## Example

```python
from unipile.models.get_calendars_list200_response_data_inner import GetCalendarsList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarsList200ResponseDataInner from a JSON string
get_calendars_list200_response_data_inner_instance = GetCalendarsList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetCalendarsList200ResponseDataInner.to_json())

# convert the object into a dict
get_calendars_list200_response_data_inner_dict = get_calendars_list200_response_data_inner_instance.to_dict()
# create an instance of GetCalendarsList200ResponseDataInner from a dict
get_calendars_list200_response_data_inner_from_dict = GetCalendarsList200ResponseDataInner.from_dict(get_calendars_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


