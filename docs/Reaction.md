# Reaction


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reaction** | **str** | The reaction added or removed. | 
**reason** | **str** | Specifies whether the reaction was added or removed. | 
**message_id** | **str** | ID of the message to which the reaction was added or removed. | 

## Example

```python
from unipile.models.reaction import Reaction

# TODO update the JSON string below
json = "{}"
# create an instance of Reaction from a JSON string
reaction_instance = Reaction.from_json(json)
# print the JSON string representation of the object
print(Reaction.to_json())

# convert the object into a dict
reaction_dict = reaction_instance.to_dict()
# create an instance of Reaction from a dict
reaction_from_dict = Reaction.from_dict(reaction_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


