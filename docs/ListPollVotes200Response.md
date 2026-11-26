# ListPollVotes200Response

A list of votes on a poll.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[ListPollVotes200ResponseDataInner]**](ListPollVotes200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the provider. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.list_poll_votes200_response import ListPollVotes200Response

# TODO update the JSON string below
json = "{}"
# create an instance of ListPollVotes200Response from a JSON string
list_poll_votes200_response_instance = ListPollVotes200Response.from_json(json)
# print the JSON string representation of the object
print(ListPollVotes200Response.to_json())

# convert the object into a dict
list_poll_votes200_response_dict = list_poll_votes200_response_instance.to_dict()
# create an instance of ListPollVotes200Response from a dict
list_poll_votes200_response_from_dict = ListPollVotes200Response.from_dict(list_poll_votes200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


