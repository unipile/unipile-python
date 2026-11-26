# CreateRelationRequestRequestSpecifics

Provider-specific options for the relation request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**linkedin** | [**LinkedIn3**](LinkedIn3.md) |  | [optional] 

## Example

```python
from unipile.models.create_relation_request_request_specifics import CreateRelationRequestRequestSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of CreateRelationRequestRequestSpecifics from a JSON string
create_relation_request_request_specifics_instance = CreateRelationRequestRequestSpecifics.from_json(json)
# print the JSON string representation of the object
print(CreateRelationRequestRequestSpecifics.to_json())

# convert the object into a dict
create_relation_request_request_specifics_dict = create_relation_request_request_specifics_instance.to_dict()
# create an instance of CreateRelationRequestRequestSpecifics from a dict
create_relation_request_request_specifics_from_dict = CreateRelationRequestRequestSpecifics.from_dict(create_relation_request_request_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


