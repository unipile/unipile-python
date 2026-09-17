# CreateScope200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the returned object. | 
**id** | **str** | The unique public ID of the Scope. | 
**application_id** | **str** | The ID of the Application that owns the Scope. | 
**name** | **str** | The internal name of the Scope. | 
**reference** | **str** | External metadata used to map the Scope to another resource, or &#x60;null&#x60; when none is defined. | 
**status** | **str** | The status of the Scope. A disabled scope blocks its scoped API keys and authentication flows until it is enabled again. | 
**created_at** | **str** | The date and time when the Scope was created. | 
**accounts_count** | **float** | The number of Accounts permanently assigned to the Scope. | 
**api_keys_count** | **float** | The number of API Keys assigned to the Scope. | 

## Example

```python
from unipile.models.create_scope200_response import CreateScope200Response

# TODO update the JSON string below
json = "{}"
# create an instance of CreateScope200Response from a JSON string
create_scope200_response_instance = CreateScope200Response.from_json(json)
# print the JSON string representation of the object
print(CreateScope200Response.to_json())

# convert the object into a dict
create_scope200_response_dict = create_scope200_response_instance.to_dict()
# create an instance of CreateScope200Response from a dict
create_scope200_response_from_dict = CreateScope200Response.from_dict(create_scope200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


