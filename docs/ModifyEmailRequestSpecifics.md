# ModifyEmailRequestSpecifics


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**outlook** | [**ModifyEmailRequestSpecificsAllOfOutlook**](ModifyEmailRequestSpecificsAllOfOutlook.md) |  | [optional] 

## Example

```python
from unipile.models.modify_email_request_specifics import ModifyEmailRequestSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of ModifyEmailRequestSpecifics from a JSON string
modify_email_request_specifics_instance = ModifyEmailRequestSpecifics.from_json(json)
# print the JSON string representation of the object
print(ModifyEmailRequestSpecifics.to_json())

# convert the object into a dict
modify_email_request_specifics_dict = modify_email_request_specifics_instance.to_dict()
# create an instance of ModifyEmailRequestSpecifics from a dict
modify_email_request_specifics_from_dict = ModifyEmailRequestSpecifics.from_dict(modify_email_request_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


