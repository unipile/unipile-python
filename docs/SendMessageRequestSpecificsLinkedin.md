# SendMessageRequestSpecificsLinkedin

Specific options to apply if the provider of the targeted account is Linkedin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**classic** | [**LinkedInClassic1**](LinkedInClassic1.md) |  | [optional] 

## Example

```python
from unipile.models.send_message_request_specifics_linkedin import SendMessageRequestSpecificsLinkedin

# TODO update the JSON string below
json = "{}"
# create an instance of SendMessageRequestSpecificsLinkedin from a JSON string
send_message_request_specifics_linkedin_instance = SendMessageRequestSpecificsLinkedin.from_json(json)
# print the JSON string representation of the object
print(SendMessageRequestSpecificsLinkedin.to_json())

# convert the object into a dict
send_message_request_specifics_linkedin_dict = send_message_request_specifics_linkedin_instance.to_dict()
# create an instance of SendMessageRequestSpecificsLinkedin from a dict
send_message_request_specifics_linkedin_from_dict = SendMessageRequestSpecificsLinkedin.from_dict(send_message_request_specifics_linkedin_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


