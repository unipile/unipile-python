# DateAndTime

A date and time.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Indicates a date-time value. | 
**date_time** | **str** | The date and time. May include a UTC offset, or be expressed as a local date and time without an offset (e.g. &#x60;2026-10-08T10:00:00&#x60;). When no offset is provided, the value is interpreted in &#x60;timezone&#x60;, or in the event-level timezone when set; otherwise it defaults to UTC. | 
**timezone** | **str** | The IANA timezone in which the date and time is expressed (e.g. &#x60;Europe/Paris&#x60;). When omitted, uses the event-level timezone if set; otherwise defaults to UTC. | [optional] 

## Example

```python
from unipile.models.date_and_time import DateAndTime

# TODO update the JSON string below
json = "{}"
# create an instance of DateAndTime from a JSON string
date_and_time_instance = DateAndTime.from_json(json)
# print the JSON string representation of the object
print(DateAndTime.to_json())

# convert the object into a dict
date_and_time_dict = date_and_time_instance.to_dict()
# create an instance of DateAndTime from a dict
date_and_time_from_dict = DateAndTime.from_dict(date_and_time_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


