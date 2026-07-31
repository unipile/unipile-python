# WhatsApp1

WhatsApp specific dataset for user profiles.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**contact_name** | **str** | Name saved by the connected account owner in their WhatsApp address book. | [optional] 

## Example

```python
from unipile.models.whats_app1 import WhatsApp1

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsApp1 from a JSON string
whats_app1_instance = WhatsApp1.from_json(json)
# print the JSON string representation of the object
print(WhatsApp1.to_json())

# convert the object into a dict
whats_app1_dict = whats_app1_instance.to_dict()
# create an instance of WhatsApp1 from a dict
whats_app1_from_dict = WhatsApp1.from_dict(whats_app1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


