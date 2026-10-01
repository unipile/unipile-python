# GetMessagesList200ResponseDataInnerSpecificsAllOfAnyOf


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | The category of the message: a regular message, an email, a connection invitation, or an InMail lifecycle event. | 
**subject** | **str** | The subject of the message. | [optional] 

## Example

```python
from unipile.models.get_messages_list200_response_data_inner_specifics_all_of_any_of import GetMessagesList200ResponseDataInnerSpecificsAllOfAnyOf

# TODO update the JSON string below
json = "{}"
# create an instance of GetMessagesList200ResponseDataInnerSpecificsAllOfAnyOf from a JSON string
get_messages_list200_response_data_inner_specifics_all_of_any_of_instance = GetMessagesList200ResponseDataInnerSpecificsAllOfAnyOf.from_json(json)
# print the JSON string representation of the object
print(GetMessagesList200ResponseDataInnerSpecificsAllOfAnyOf.to_json())

# convert the object into a dict
get_messages_list200_response_data_inner_specifics_all_of_any_of_dict = get_messages_list200_response_data_inner_specifics_all_of_any_of_instance.to_dict()
# create an instance of GetMessagesList200ResponseDataInnerSpecificsAllOfAnyOf from a dict
get_messages_list200_response_data_inner_specifics_all_of_any_of_from_dict = GetMessagesList200ResponseDataInnerSpecificsAllOfAnyOf.from_dict(get_messages_list200_response_data_inner_specifics_all_of_any_of_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


