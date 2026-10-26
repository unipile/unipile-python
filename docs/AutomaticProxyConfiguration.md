# AutomaticProxyConfiguration

Country preferences for automatic proxy assignment. Explicitly selected countries must be part of Unipile’s proxy offering for the provider. If omitted, Unipile determines the preferred country automatically. The fallback setting determines whether an available proxy from another country may be used when no proxy is available in the preferred country.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**country** | **str** | An ISO 3166-1 alpha-2 country code for the automatic proxy location, normalized to uppercase. Choose from the &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/docs/proxys#countries\&quot;&gt;countries where Unipile offers automatic proxies&lt;/a&gt;. A proxy may be temporarily unavailable even in a country included in the offering. | [optional] 
**ip** | **str** | An IPv4 address used to infer the automatic proxy location. If Unipile does not offer proxies in the inferred country, or no proxy is currently available there, allow_country_fallback controls whether an available proxy from another country may be used. | [optional] 
**allow_country_fallback** | **bool** | Whether an available proxy from another country may be used when none is available in the rotation country, during authentication and throughout the account lifetime. Defaults to true. An explicitly selected country must be part of Unipile’s proxy offering for the provider, even when fallback is allowed. A proxy may be temporarily unavailable in a country included in the offering. Authentication fails if no proxy is available in any allowed country. If false, authentication fails when no proxy is available in the rotation country. If the selected proxy later fails and no replacement is available there, the account enters Service interruption. Rotation to another available proxy in that country remains allowed. | [optional] [default to True]

## Example

```python
from unipile.models.automatic_proxy_configuration import AutomaticProxyConfiguration

# TODO update the JSON string below
json = "{}"
# create an instance of AutomaticProxyConfiguration from a JSON string
automatic_proxy_configuration_instance = AutomaticProxyConfiguration.from_json(json)
# print the JSON string representation of the object
print(AutomaticProxyConfiguration.to_json())

# convert the object into a dict
automatic_proxy_configuration_dict = automatic_proxy_configuration_instance.to_dict()
# create an instance of AutomaticProxyConfiguration from a dict
automatic_proxy_configuration_from_dict = AutomaticProxyConfiguration.from_dict(automatic_proxy_configuration_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


