# CreateFolder201Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the folder for the provider. | 
**name** | **str** | The name of the folder. | 
**role** | **str** | The system role of the folder. | [optional] 
**total_count** | **float** | The total number of emails in the folder. For Gmail, the total number of emails assigned with this label. | 
**unread_count** | **float** | The number of unread emails in the folder. For Gmail, the number of unread emails assigned with this label. | 
**background_color** | **str** | (Gmail Only) The background color of the folder. | [optional] 
**text_color** | **str** | (Gmail Only) The text color of the folder. | [optional] 
**is_system** | **bool** | (Gmail Only) If &#x60;true&#x60;, the label is created by Google. If &#x60;false&#x60;, the label was created by the user. | [optional] 
**parent_id** | **str** | (Outlook only) The ID of the parent folder. | [optional] 

## Example

```python
from unipile.models.create_folder201_response import CreateFolder201Response

# TODO update the JSON string below
json = "{}"
# create an instance of CreateFolder201Response from a JSON string
create_folder201_response_instance = CreateFolder201Response.from_json(json)
# print the JSON string representation of the object
print(CreateFolder201Response.to_json())

# convert the object into a dict
create_folder201_response_dict = create_folder201_response_instance.to_dict()
# create an instance of CreateFolder201Response from a dict
create_folder201_response_from_dict = CreateFolder201Response.from_dict(create_folder201_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


