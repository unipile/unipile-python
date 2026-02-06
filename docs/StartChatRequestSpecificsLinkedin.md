# StartChatRequestSpecificsLinkedin

Specific options to apply if the provider of the targeted account is Linkedin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**classic** | [**LinkedInClassic**](LinkedInClassic.md) |  | [optional] 
**sales_navigator** | [**LinkedInSalesNavigator**](LinkedInSalesNavigator.md) |  | [optional] 
**recruiter** | [**LinkedInRecruiter**](LinkedInRecruiter.md) |  | [optional] 

## Example

```python
from unipile.models.start_chat_request_specifics_linkedin import StartChatRequestSpecificsLinkedin

# TODO update the JSON string below
json = "{}"
# create an instance of StartChatRequestSpecificsLinkedin from a JSON string
start_chat_request_specifics_linkedin_instance = StartChatRequestSpecificsLinkedin.from_json(json)
# print the JSON string representation of the object
print(StartChatRequestSpecificsLinkedin.to_json())

# convert the object into a dict
start_chat_request_specifics_linkedin_dict = start_chat_request_specifics_linkedin_instance.to_dict()
# create an instance of StartChatRequestSpecificsLinkedin from a dict
start_chat_request_specifics_linkedin_from_dict = StartChatRequestSpecificsLinkedin.from_dict(start_chat_request_specifics_linkedin_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


