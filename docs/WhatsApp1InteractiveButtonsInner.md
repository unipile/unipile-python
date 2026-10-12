# WhatsApp1InteractiveButtonsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**id** | **str** | Provider button identifier, when available. | [optional] 
**text** | **str** | Button label, when available. | [optional] 
**url** | **str** | The text content of the message, when available. | [optional] 
**phone_number** | **str** | The text content of the message, when available. | [optional] 
**name** | **str** | Native flow action name. Unknown actions are not interpreted. | [optional] 

## Example

```python
from unipile.models.whats_app1_interactive_buttons_inner import WhatsApp1InteractiveButtonsInner

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsApp1InteractiveButtonsInner from a JSON string
whats_app1_interactive_buttons_inner_instance = WhatsApp1InteractiveButtonsInner.from_json(json)
# print the JSON string representation of the object
print(WhatsApp1InteractiveButtonsInner.to_json())

# convert the object into a dict
whats_app1_interactive_buttons_inner_dict = whats_app1_interactive_buttons_inner_instance.to_dict()
# create an instance of WhatsApp1InteractiveButtonsInner from a dict
whats_app1_interactive_buttons_inner_from_dict = WhatsApp1InteractiveButtonsInner.from_dict(whats_app1_interactive_buttons_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


