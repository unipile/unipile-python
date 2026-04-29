# GetUserChat200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**data** | [**List[GetUserChat200ResponseDataInner]**](GetUserChat200ResponseDataInner.md) | Resolved chats associated with the given user. Empty if none could be resolved. | 

## Example

```python
from unipile.models.get_user_chat200_response import GetUserChat200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserChat200Response from a JSON string
get_user_chat200_response_instance = GetUserChat200Response.from_json(json)
# print the JSON string representation of the object
print(GetUserChat200Response.to_json())

# convert the object into a dict
get_user_chat200_response_dict = get_user_chat200_response_instance.to_dict()
# create an instance of GetUserChat200Response from a dict
get_user_chat200_response_from_dict = GetUserChat200Response.from_dict(get_user_chat200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


