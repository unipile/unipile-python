# ModifyEmailRequestSpecificsAllOfOutlook

Specific options to apply if the provider of the targeted account is Outlook.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**categories** | **List[str]** | List of categories to assign to the email. | [optional] 

## Example

```python
from unipile.models.modify_email_request_specifics_all_of_outlook import ModifyEmailRequestSpecificsAllOfOutlook

# TODO update the JSON string below
json = "{}"
# create an instance of ModifyEmailRequestSpecificsAllOfOutlook from a JSON string
modify_email_request_specifics_all_of_outlook_instance = ModifyEmailRequestSpecificsAllOfOutlook.from_json(json)
# print the JSON string representation of the object
print(ModifyEmailRequestSpecificsAllOfOutlook.to_json())

# convert the object into a dict
modify_email_request_specifics_all_of_outlook_dict = modify_email_request_specifics_all_of_outlook_instance.to_dict()
# create an instance of ModifyEmailRequestSpecificsAllOfOutlook from a dict
modify_email_request_specifics_all_of_outlook_from_dict = ModifyEmailRequestSpecificsAllOfOutlook.from_dict(modify_email_request_specifics_all_of_outlook_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


