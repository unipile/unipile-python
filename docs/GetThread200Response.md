# GetThread200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the thread. | 
**emails** | [**List[GetThread200ResponseEmailsInner]**](GetThread200ResponseEmailsInner.md) |  | 

## Example

```python
from unipile.models.get_thread200_response import GetThread200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetThread200Response from a JSON string
get_thread200_response_instance = GetThread200Response.from_json(json)
# print the JSON string representation of the object
print(GetThread200Response.to_json())

# convert the object into a dict
get_thread200_response_dict = get_thread200_response_instance.to_dict()
# create an instance of GetThread200Response from a dict
get_thread200_response_from_dict = GetThread200Response.from_dict(get_thread200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


