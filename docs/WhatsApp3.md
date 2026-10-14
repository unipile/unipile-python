# WhatsApp3

WhatsApp specific dataset for user profiles.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**contact_name** | **str** | Name saved by the connected account owner in their WhatsApp address book. | [optional] 

## Example

```python
from unipile.models.whats_app3 import WhatsApp3

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsApp3 from a JSON string
whats_app3_instance = WhatsApp3.from_json(json)
# print the JSON string representation of the object
print(WhatsApp3.to_json())

# convert the object into a dict
whats_app3_dict = whats_app3_instance.to_dict()
# create an instance of WhatsApp3 from a dict
whats_app3_from_dict = WhatsApp3.from_dict(whats_app3_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


