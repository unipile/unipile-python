# ListScopes200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the returned object. | 
**id** | **str** | The unique public ID of the Scope. | 
**application_id** | **str** | The ID of the Application that owns the Scope. | 
**name** | **str** | The internal name of the Scope. | 
**reference** | **str** | The text content of the message, when available. | 
**status** | **str** | The status of the Scope. A disabled scope blocks its scoped API keys and authentication flows until it is enabled again. | 
**created_at** | **str** | The date and time when the Scope was created. | 
**accounts_count** | **float** | The number of Accounts permanently assigned to the Scope. | 
**api_keys_count** | **float** | The number of API Keys assigned to the Scope. | 

## Example

```python
from unipile.models.list_scopes200_response_data_inner import ListScopes200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of ListScopes200ResponseDataInner from a JSON string
list_scopes200_response_data_inner_instance = ListScopes200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(ListScopes200ResponseDataInner.to_json())

# convert the object into a dict
list_scopes200_response_data_inner_dict = list_scopes200_response_data_inner_instance.to_dict()
# create an instance of ListScopes200ResponseDataInner from a dict
list_scopes200_response_data_inner_from_dict = ListScopes200ResponseDataInner.from_dict(list_scopes200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


