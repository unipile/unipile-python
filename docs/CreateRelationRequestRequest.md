# CreateRelationRequestRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message** | **str** | A message to send to the user along with the request (if supported by the provider). | [optional] 
**user_id** | **str** | The ID of the User to request a bi-directional relation with. | 

## Example

```python
from unipile.models.create_relation_request_request import CreateRelationRequestRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateRelationRequestRequest from a JSON string
create_relation_request_request_instance = CreateRelationRequestRequest.from_json(json)
# print the JSON string representation of the object
print(CreateRelationRequestRequest.to_json())

# convert the object into a dict
create_relation_request_request_dict = create_relation_request_request_instance.to_dict()
# create an instance of CreateRelationRequestRequest from a dict
create_relation_request_request_from_dict = CreateRelationRequestRequest.from_dict(create_relation_request_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


