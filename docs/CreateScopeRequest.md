# CreateScopeRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | An internal name used to identify the Scope. | 
**reference** | **str** | Optional metadata used to map the Scope to an external resource. Must be unique in the Application. | [optional] 

## Example

```python
from unipile.models.create_scope_request import CreateScopeRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateScopeRequest from a JSON string
create_scope_request_instance = CreateScopeRequest.from_json(json)
# print the JSON string representation of the object
print(CreateScopeRequest.to_json())

# convert the object into a dict
create_scope_request_dict = create_scope_request_instance.to_dict()
# create an instance of CreateScopeRequest from a dict
create_scope_request_from_dict = CreateScopeRequest.from_dict(create_scope_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


