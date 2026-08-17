# GetContactsList200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[GetContactsList200ResponseDataInner]**](GetContactsList200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the provider. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.get_contacts_list200_response import GetContactsList200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetContactsList200Response from a JSON string
get_contacts_list200_response_instance = GetContactsList200Response.from_json(json)
# print the JSON string representation of the object
print(GetContactsList200Response.to_json())

# convert the object into a dict
get_contacts_list200_response_dict = get_contacts_list200_response_instance.to_dict()
# create an instance of GetContactsList200Response from a dict
get_contacts_list200_response_from_dict = GetContactsList200Response.from_dict(get_contacts_list200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


