# GetInboxesList200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | ID of the Inbox. | 
**description** | **str** | Description of the Inbox. | [optional] 
**disabled** | **bool** | Whether messaging is currently disabled for the Inbox. | 

## Example

```python
from unipile.models.get_inboxes_list200_response_data_inner import GetInboxesList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetInboxesList200ResponseDataInner from a JSON string
get_inboxes_list200_response_data_inner_instance = GetInboxesList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetInboxesList200ResponseDataInner.to_json())

# convert the object into a dict
get_inboxes_list200_response_data_inner_dict = get_inboxes_list200_response_data_inner_instance.to_dict()
# create an instance of GetInboxesList200ResponseDataInner from a dict
get_inboxes_list200_response_data_inner_from_dict = GetInboxesList200ResponseDataInner.from_dict(get_inboxes_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


