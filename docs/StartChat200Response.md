# StartChat200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**chat_id** | **str** | The ID of the started chat. | 
**message_id** | [**StartChat200ResponseMessageId**](StartChat200ResponseMessageId.md) |  | 

## Example

```python
from unipile.models.start_chat200_response import StartChat200Response

# TODO update the JSON string below
json = "{}"
# create an instance of StartChat200Response from a JSON string
start_chat200_response_instance = StartChat200Response.from_json(json)
# print the JSON string representation of the object
print(StartChat200Response.to_json())

# convert the object into a dict
start_chat200_response_dict = start_chat200_response_instance.to_dict()
# create an instance of StartChat200Response from a dict
start_chat200_response_from_dict = StartChat200Response.from_dict(start_chat200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


