# SendEmail200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the email. | 
**message_id** | **str** | The Message-ID header value of the email. Use &#x60;id&#x60; in Unipile requests. | 

## Example

```python
from unipile.models.send_email200_response import SendEmail200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SendEmail200Response from a JSON string
send_email200_response_instance = SendEmail200Response.from_json(json)
# print the JSON string representation of the object
print(SendEmail200Response.to_json())

# convert the object into a dict
send_email200_response_dict = send_email200_response_instance.to_dict()
# create an instance of SendEmail200Response from a dict
send_email200_response_from_dict = SendEmail200Response.from_dict(send_email200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


