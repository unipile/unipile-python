# CompaniesSearchDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**id** | **str** | The ID of the Company. | 
**display_name** | **str** | The display name of the Company. | 
**public_identifier** | **str** | The public identifier of the Company. | [optional] 
**profile_url** | **str** | The profile URL of the Company. | [optional] 
**public_picture_url** | **str** | The public picture URL of the Company. | [optional] 
**public_picture_url_large** | **str** | The public picture URL of the Company in large size. | [optional] 
**location** | **str** | The location of the Company. | [optional] 
**industry** | **str** | The industry to which the Company belongs. | [optional] 
**summary** | **str** | The summary of the Company&#39;s activities. | [optional] 
**relations_count** | **float** | The number of the relations of the Company. | [optional] 
**product** | **str** |  | 
**type** | **str** | The type of the Company. | [optional] 
**headcount** | **float** | The number of employees of the Company. | [optional] 
**specialties** | **List[Optional[str]]** | A list of the company&#39;s activities. | [optional] 
**is_hiring_on_linkedin** | **bool** | Whether the Company is hiring on LinkedIn. | [optional] 
**lists_count** | **float** | The number of lists you own on which the Company appears. | 
**notes_count** | **float** | The number of notes you own about the Company. | 
**website** | **str** | The webiste URL of the Company. | [optional] 
**founded_on** | **float** | The date on which the Company was founded. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**has_been_saved** | **bool** | Whether the Company has been saved to a list. | 
**is_starred** | **bool** | Whether the Company is on starred state. | 

## Example

```python
from unipile.models.companies_search_data_inner import CompaniesSearchDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of CompaniesSearchDataInner from a JSON string
companies_search_data_inner_instance = CompaniesSearchDataInner.from_json(json)
# print the JSON string representation of the object
print(CompaniesSearchDataInner.to_json())

# convert the object into a dict
companies_search_data_inner_dict = companies_search_data_inner_instance.to_dict()
# create an instance of CompaniesSearchDataInner from a dict
companies_search_data_inner_from_dict = CompaniesSearchDataInner.from_dict(companies_search_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


