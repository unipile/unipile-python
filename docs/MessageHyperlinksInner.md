# MessageHyperlinksInner

The parameters of an external hyperlink contained in the body.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**url** | **str** | The URL the link points to. | 
**starts_at** | **float** | The index in the body where the link starts. | 
**length** | **float** | The number of characters in the body that make up the link, starting at the &#x60;starts_at&#x60; index. | 

## Example

```python
from unipile.models.message_hyperlinks_inner import MessageHyperlinksInner

# TODO update the JSON string below
json = "{}"
# create an instance of MessageHyperlinksInner from a JSON string
message_hyperlinks_inner_instance = MessageHyperlinksInner.from_json(json)
# print the JSON string representation of the object
print(MessageHyperlinksInner.to_json())

# convert the object into a dict
message_hyperlinks_inner_dict = message_hyperlinks_inner_instance.to_dict()
# create an instance of MessageHyperlinksInner from a dict
message_hyperlinks_inner_from_dict = MessageHyperlinksInner.from_dict(message_hyperlinks_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


