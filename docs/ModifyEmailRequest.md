# ModifyEmailRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**folders_ids** | **List[Optional[str]]** | The ID(s) of the folder(s) to apply, overwriting all folders previously associated with the Email. Outlook emails can be in a single folder only. Google allows a single email to appear in multiple folders. | [optional] 
**specifics** | [**ModifyEmailRequestSpecifics**](ModifyEmailRequestSpecifics.md) |  | [optional] 

## Example

```python
from unipile.models.modify_email_request import ModifyEmailRequest

# TODO update the JSON string below
json = "{}"
# create an instance of ModifyEmailRequest from a JSON string
modify_email_request_instance = ModifyEmailRequest.from_json(json)
# print the JSON string representation of the object
print(ModifyEmailRequest.to_json())

# convert the object into a dict
modify_email_request_dict = modify_email_request_instance.to_dict()
# create an instance of ModifyEmailRequest from a dict
modify_email_request_from_dict = ModifyEmailRequest.from_dict(modify_email_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


