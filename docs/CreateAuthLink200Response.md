# CreateAuthLink200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**link** | **str** | Link to the Hosted Auth session. Redirect your users to this link so they can authenticate their account. | 

## Example

```python
from unipile.models.create_auth_link200_response import CreateAuthLink200Response

# TODO update the JSON string below
json = "{}"
# create an instance of CreateAuthLink200Response from a JSON string
create_auth_link200_response_instance = CreateAuthLink200Response.from_json(json)
# print the JSON string representation of the object
print(CreateAuthLink200Response.to_json())

# convert the object into a dict
create_auth_link200_response_dict = create_auth_link200_response_instance.to_dict()
# create an instance of CreateAuthLink200Response from a dict
create_auth_link200_response_from_dict = CreateAuthLink200Response.from_dict(create_auth_link200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


