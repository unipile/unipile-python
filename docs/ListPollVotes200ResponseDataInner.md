# ListPollVotes200ResponseDataInner

A vote on a poll.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object. | 
**option_id** | **str** | The ID of the chosen option, matching the &#x60;poll.options[].id&#x60; of the post. | 
**voter** | [**ListPollVotes200ResponseDataInnerVoter**](ListPollVotes200ResponseDataInnerVoter.md) |  | 

## Example

```python
from unipile.models.list_poll_votes200_response_data_inner import ListPollVotes200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of ListPollVotes200ResponseDataInner from a JSON string
list_poll_votes200_response_data_inner_instance = ListPollVotes200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(ListPollVotes200ResponseDataInner.to_json())

# convert the object into a dict
list_poll_votes200_response_data_inner_dict = list_poll_votes200_response_data_inner_instance.to_dict()
# create an instance of ListPollVotes200ResponseDataInner from a dict
list_poll_votes200_response_data_inner_from_dict = ListPollVotes200ResponseDataInner.from_dict(list_poll_votes200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


