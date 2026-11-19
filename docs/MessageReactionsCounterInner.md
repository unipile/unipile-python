# MessageReactionsCounterInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reaction** | **str** | Value of the reaction. Usually an emoji unicode. | 
**count** | **float** | The total count of this reaction. | 

## Example

```python
from unipile.models.message_reactions_counter_inner import MessageReactionsCounterInner

# TODO update the JSON string below
json = "{}"
# create an instance of MessageReactionsCounterInner from a JSON string
message_reactions_counter_inner_instance = MessageReactionsCounterInner.from_json(json)
# print the JSON string representation of the object
print(MessageReactionsCounterInner.to_json())

# convert the object into a dict
message_reactions_counter_inner_dict = message_reactions_counter_inner_instance.to_dict()
# create an instance of MessageReactionsCounterInner from a dict
message_reactions_counter_inner_from_dict = MessageReactionsCounterInner.from_dict(message_reactions_counter_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


