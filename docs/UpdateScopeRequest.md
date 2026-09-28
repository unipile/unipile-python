# UpdateScopeRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The new internal name of the Scope. | [optional] 
**reference** | **str** | The new external reference of the Scope. Must be unique in the Application. Set to &#x60;null&#x60; to remove it. | [optional] 
**status** | **str** | The status of the Scope. A disabled scope blocks its scoped API keys and authentication flows until it is enabled again. | [optional] 

## Example

```python
from unipile.models.update_scope_request import UpdateScopeRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateScopeRequest from a JSON string
update_scope_request_instance = UpdateScopeRequest.from_json(json)
# print the JSON string representation of the object
print(UpdateScopeRequest.to_json())

# convert the object into a dict
update_scope_request_dict = update_scope_request_instance.to_dict()
# create an instance of UpdateScopeRequest from a dict
update_scope_request_from_dict = UpdateScopeRequest.from_dict(update_scope_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


