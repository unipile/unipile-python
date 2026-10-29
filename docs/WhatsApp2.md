# WhatsApp2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**interactive** | [**WhatsApp2Interactive**](WhatsApp2Interactive.md) |  | [optional] 
**album_id** | **str** | Identifier of the media album the message belongs to. Messages sent together as one album share the same value. Absent when the message is not part of an album. | [optional] 

## Example

```python
from unipile.models.whats_app2 import WhatsApp2

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsApp2 from a JSON string
whats_app2_instance = WhatsApp2.from_json(json)
# print the JSON string representation of the object
print(WhatsApp2.to_json())

# convert the object into a dict
whats_app2_dict = whats_app2_instance.to_dict()
# create an instance of WhatsApp2 from a dict
whats_app2_from_dict = WhatsApp2.from_dict(whats_app2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


