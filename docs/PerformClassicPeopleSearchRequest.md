# PerformClassicPeopleSearchRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**keywords** | **str** | A keyword or group of keywords. | [optional] 
**network_distance** | **List[float]** | A list of connection degrees (1 for First, 2 for Second and 3 for Third+).    Native filter : Connections    | [optional] 
**location** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;LOCATION&#x60; type to find out the possible values.    Native filter : Locations    | [optional] 
**current_company** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;COMPANY&#x60; type to find out the possible values.    Native filter : Current company    | [optional] 
**past_company** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;COMPANY&#x60; type to find out the possible values.    Native filter : Past company    | [optional] 
**school** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SCHOOL&#x60; type to find out the possible values.    Native filter : School    | [optional] 
**connections_of** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;RELATION&#x60; type to find out the possible values.    Native filter : Connections of    | [optional] 
**followers_of** | **str** | A parameter ID. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;PEOPLE&#x60; type to find out the possible values.    Native filter : Followers of    | [optional] 
**industry** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;INDUSTRY&#x60; type to find out the possible values.    Native filter : Industry    | [optional] 
**service** | **List[Optional[str]]** | A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SERVICE&#x60; type to find out the possible values.    Native filter : Service categories    | [optional] 
**profile_language** | **List[str]** | A list of ISO 639-1 language codes.    Native filter : Profile language    | [optional] 
**open_to_volunteering** | **bool** | Whether the users should be open to volunteering.    Native filter : Open to Volunteering     | [optional] 
**advanced_keywords** | [**PerformClassicPeopleSearchRequestAdvancedKeywords**](PerformClassicPeopleSearchRequestAdvancedKeywords.md) |  | [optional] 

## Example

```python
from unipile.models.perform_classic_people_search_request import PerformClassicPeopleSearchRequest

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicPeopleSearchRequest from a JSON string
perform_classic_people_search_request_instance = PerformClassicPeopleSearchRequest.from_json(json)
# print the JSON string representation of the object
print(PerformClassicPeopleSearchRequest.to_json())

# convert the object into a dict
perform_classic_people_search_request_dict = perform_classic_people_search_request_instance.to_dict()
# create an instance of PerformClassicPeopleSearchRequest from a dict
perform_classic_people_search_request_from_dict = PerformClassicPeopleSearchRequest.from_dict(perform_classic_people_search_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


