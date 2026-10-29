# GetMessage200ResponseSpecifics


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | The category of the message: a regular message, an email, a connection invitation, or an InMail lifecycle event. | 
**subject** | **str** | The subject of the mock message. | 
**interactive** | [**WhatsApp2Interactive**](WhatsApp2Interactive.md) |  | [optional] 
**album_id** | **str** | Identifier of the media album the message belongs to. Messages sent together as one album share the same value. Absent when the message is not part of an album. | [optional] 

## Example

```python
from unipile.models.get_message200_response_specifics import GetMessage200ResponseSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of GetMessage200ResponseSpecifics from a JSON string
get_message200_response_specifics_instance = GetMessage200ResponseSpecifics.from_json(json)
# print the JSON string representation of the object
print(GetMessage200ResponseSpecifics.to_json())

# convert the object into a dict
get_message200_response_specifics_dict = get_message200_response_specifics_instance.to_dict()
# create an instance of GetMessage200ResponseSpecifics from a dict
get_message200_response_specifics_from_dict = GetMessage200ResponseSpecifics.from_dict(get_message200_response_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


