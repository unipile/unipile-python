# CreateFolderRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the folder. For Gmail, name of the label. | 
**parent_id** | **str** | (Outlook only) ID of the parent folder. | [optional] 
**text_color** | **str** | (Gmail only) Hexadecimal color code for the text of the label. | [optional] 
**background_color** | **str** | (Gmail only) Hexadecimal color code for the background of the label. | [optional] 

## Example

```python
from unipile.models.create_folder_request import CreateFolderRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateFolderRequest from a JSON string
create_folder_request_instance = CreateFolderRequest.from_json(json)
# print the JSON string representation of the object
print(CreateFolderRequest.to_json())

# convert the object into a dict
create_folder_request_dict = create_folder_request_instance.to_dict()
# create an instance of CreateFolderRequest from a dict
create_folder_request_from_dict = CreateFolderRequest.from_dict(create_folder_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


