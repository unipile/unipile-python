# WhatsApp2Interactive

WhatsApp interactive content available in the received provider payload. The body is exposed in text. Supports buttons, hydrated templates and native flows; missing or unsupported payloads cannot be reconstructed. Button metadata does not imply that Unipile can execute the action.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**title** | **str** |  | [optional] 
**footer** | **str** |  | [optional] 
**buttons** | [**List[WhatsApp1InteractiveSelectedButton]**](WhatsApp1InteractiveSelectedButton.md) |  | 
**selected_button** | [**WhatsApp1InteractiveSelectedButton**](WhatsApp1InteractiveSelectedButton.md) |  | [optional] 

## Example

```python
from unipile.models.whats_app2_interactive import WhatsApp2Interactive

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsApp2Interactive from a JSON string
whats_app2_interactive_instance = WhatsApp2Interactive.from_json(json)
# print the JSON string representation of the object
print(WhatsApp2Interactive.to_json())

# convert the object into a dict
whats_app2_interactive_dict = whats_app2_interactive_instance.to_dict()
# create an instance of WhatsApp2Interactive from a dict
whats_app2_interactive_from_dict = WhatsApp2Interactive.from_dict(whats_app2_interactive_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


