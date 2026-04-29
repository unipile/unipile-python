# LinkedInClassic

Specific options for a LinkedIn classic chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inmail** | **bool** | Whether the chat should be started with an InMail. | [optional] [default to False]
**company_topic** | **str** | The topic for a conversation with a company. | [optional] [default to 'SERVICE_REQUEST']
**relation_request_id** | **str** | If you&#39;d like to start a conversation with a user you received a relation request from, the ID of the request is mandatory. | [optional] 
**applicant** | [**LinkedInClassicApplicant**](LinkedInClassicApplicant.md) |  | [optional] 

## Example

```python
from unipile.models.linked_in_classic import LinkedInClassic

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInClassic from a JSON string
linked_in_classic_instance = LinkedInClassic.from_json(json)
# print the JSON string representation of the object
print(LinkedInClassic.to_json())

# convert the object into a dict
linked_in_classic_dict = linked_in_classic_instance.to_dict()
# create an instance of LinkedInClassic from a dict
linked_in_classic_from_dict = LinkedInClassic.from_dict(linked_in_classic_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


