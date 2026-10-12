# WhatsApp1InteractiveSelectedButton


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**id** | **str** | Provider button identifier, when available. | [optional] 
**text** | **str** | Button label, when available. | [optional] 
**url** | **str** |  | [optional] 
**phone_number** | **str** |  | [optional] 
**name** | **str** | Native flow action name. Unknown actions are not interpreted. | [optional] 

## Example

```python
from unipile.models.whats_app1_interactive_selected_button import WhatsApp1InteractiveSelectedButton

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsApp1InteractiveSelectedButton from a JSON string
whats_app1_interactive_selected_button_instance = WhatsApp1InteractiveSelectedButton.from_json(json)
# print the JSON string representation of the object
print(WhatsApp1InteractiveSelectedButton.to_json())

# convert the object into a dict
whats_app1_interactive_selected_button_dict = whats_app1_interactive_selected_button_instance.to_dict()
# create an instance of WhatsApp1InteractiveSelectedButton from a dict
whats_app1_interactive_selected_button_from_dict = WhatsApp1InteractiveSelectedButton.from_dict(whats_app1_interactive_selected_button_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


