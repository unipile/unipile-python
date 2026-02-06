# LeadList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[LeadListDataInner]**](LeadListDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.lead_list import LeadList

# TODO update the JSON string below
json = "{}"
# create an instance of LeadList from a JSON string
lead_list_instance = LeadList.from_json(json)
# print the JSON string representation of the object
print(LeadList.to_json())

# convert the object into a dict
lead_list_dict = lead_list_instance.to_dict()
# create an instance of LeadList from a dict
lead_list_from_dict = LeadList.from_dict(lead_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


