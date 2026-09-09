# LinkedIn1RelationRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**user** | [**LinkedIn1RelationRequestUser**](LinkedIn1RelationRequestUser.md) |  | [optional] 
**type** | **str** | Type of the relation / follow request.       - &#x60;sent&#x60; if the current user has asked another one to be in his relations.       - &#x60;received&#x60; if another user has asked the current one to be in his relations. | 
**id** | **str** | The unique identifier of the invitation for the provider. | 
**created_at** | **str** | Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**message** | **str** | Any message that comes with the invitation. | [optional] 

## Example

```python
from unipile.models.linked_in1_relation_request import LinkedIn1RelationRequest

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1RelationRequest from a JSON string
linked_in1_relation_request_instance = LinkedIn1RelationRequest.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1RelationRequest.to_json())

# convert the object into a dict
linked_in1_relation_request_dict = linked_in1_relation_request_instance.to_dict()
# create an instance of LinkedIn1RelationRequest from a dict
linked_in1_relation_request_from_dict = LinkedIn1RelationRequest.from_dict(linked_in1_relation_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


