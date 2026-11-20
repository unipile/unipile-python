# ProcessStoppedLink

An optional resource or action to present to the account owner alongside the message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**url** | **str** | An absolute HTTP or HTTPS URL providing information or actions relevant to the stopped attempt. | 
**label** | **str** | The label describing the linked resource or action. | 

## Example

```python
from unipile.models.process_stopped_link import ProcessStoppedLink

# TODO update the JSON string below
json = "{}"
# create an instance of ProcessStoppedLink from a JSON string
process_stopped_link_instance = ProcessStoppedLink.from_json(json)
# print the JSON string representation of the object
print(ProcessStoppedLink.to_json())

# convert the object into a dict
process_stopped_link_dict = process_stopped_link_instance.to_dict()
# create an instance of ProcessStoppedLink from a dict
process_stopped_link_from_dict = ProcessStoppedLink.from_dict(process_stopped_link_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


