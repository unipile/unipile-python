# MessageMentionsInner

The parameters of a user mention contained in the body.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **str** | ID of the mentioned user, which can be used to mention them when sending a message. Absent when the provider reports the mention without an identifier, or when the mention addresses the whole chat rather than a user. | [optional] 
**url** | **str** | Public profile URL of the mentioned user. Absent when the provider exposes no public profile for them. | [optional] 
**start** | **float** | The index in the body where the mention starts. | 
**length** | **float** | The number of characters in the body that make up the mention, starting at the &#x60;start&#x60; index. | 

## Example

```python
from unipile.models.message_mentions_inner import MessageMentionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of MessageMentionsInner from a JSON string
message_mentions_inner_instance = MessageMentionsInner.from_json(json)
# print the JSON string representation of the object
print(MessageMentionsInner.to_json())

# convert the object into a dict
message_mentions_inner_dict = message_mentions_inner_instance.to_dict()
# create an instance of MessageMentionsInner from a dict
message_mentions_inner_from_dict = MessageMentionsInner.from_dict(message_mentions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


