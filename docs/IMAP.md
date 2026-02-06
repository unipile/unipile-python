# IMAP

Start the authentication intent with IMAP provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**credentials** | [**IMAPCredentials**](IMAPCredentials.md) |  | 
**config** | [**IMAPConfig**](IMAPConfig.md) |  | [optional] 

## Example

```python
from unipile.models.imap import IMAP

# TODO update the JSON string below
json = "{}"
# create an instance of IMAP from a JSON string
imap_instance = IMAP.from_json(json)
# print the JSON string representation of the object
print(IMAP.to_json())

# convert the object into a dict
imap_dict = imap_instance.to_dict()
# create an instance of IMAP from a dict
imap_from_dict = IMAP.from_dict(imap_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


