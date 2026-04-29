# GetEmailContactsList200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[GetEmailContactsList200ResponseDataInner]**](GetEmailContactsList200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.get_email_contacts_list200_response import GetEmailContactsList200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetEmailContactsList200Response from a JSON string
get_email_contacts_list200_response_instance = GetEmailContactsList200Response.from_json(json)
# print the JSON string representation of the object
print(GetEmailContactsList200Response.to_json())

# convert the object into a dict
get_email_contacts_list200_response_dict = get_email_contacts_list200_response_instance.to_dict()
# create an instance of GetEmailContactsList200Response from a dict
get_email_contacts_list200_response_from_dict = GetEmailContactsList200Response.from_dict(get_email_contacts_list200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


