# CreateApiKey200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the created object. | 
**id** | **str** | The unique public ID of the created API Key. | 
**api_key** | **str** | The secret API Key token. It is returned only once and must be stored securely. | 

## Example

```python
from unipile.models.create_api_key200_response import CreateApiKey200Response

# TODO update the JSON string below
json = "{}"
# create an instance of CreateApiKey200Response from a JSON string
create_api_key200_response_instance = CreateApiKey200Response.from_json(json)
# print the JSON string representation of the object
print(CreateApiKey200Response.to_json())

# convert the object into a dict
create_api_key200_response_dict = create_api_key200_response_instance.to_dict()
# create an instance of CreateApiKey200Response from a dict
create_api_key200_response_from_dict = CreateApiKey200Response.from_dict(create_api_key200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


