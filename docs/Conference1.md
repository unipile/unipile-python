# Conference1

A conference to generate or attach to the event.         The way the conference is associated with the event may vary depending on the calendar and the selected provider:         it can be generated and hosted natively by the provider (e.g. Google Meet on Google, Microsoft Teams or Skype on         Outlook), or, when a \"url\" is provided, attached as an existing conference whose join link is published in the         event body.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The conference provider to generate or attach. | 
**conference_id** | **str** | The conference identifier assigned by its provider. | [optional] 
**url** | **str** | The URL of an existing conference to attach to the event. Must be an absolute credential-free HTTPS URL.         When omitted, conference generation is requested. Availability depends on the calendar and the selected provider;         when generation is not supported, provide the URL of an existing conference. | [optional] 

## Example

```python
from unipile.models.conference1 import Conference1

# TODO update the JSON string below
json = "{}"
# create an instance of Conference1 from a JSON string
conference1_instance = Conference1.from_json(json)
# print the JSON string representation of the object
print(Conference1.to_json())

# convert the object into a dict
conference1_dict = conference1_instance.to_dict()
# create an instance of Conference1 from a dict
conference1_from_dict = Conference1.from_dict(conference1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


