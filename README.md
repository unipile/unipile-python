# Unipile Python SDK

Python SDK for the Unipile API.

This SDK is only for **Unipile API v2 (BETA)**.

## Installation

The package is not published on PyPI yet. Install it directly from GitHub:

```sh
pip install git+https://github.com/unipile/unipile-python.git
```

You can also pin a branch, tag, or commit:

```sh
pip install git+https://github.com/unipile/unipile-python.git@main
```

## Usage

```python
import unipile

configuration = unipile.Configuration()
configuration.api_key["apiKey"] = "apikey"

api_client = unipile.ApiClient(configuration)
messaging_api = unipile.MessagingApi(api_client)
```

For endpoint details, see the Unipile v2 API documentation.

## Links

- [Documentation](https://developer.unipile.com/v2.0/docs/welcome)
- [API Reference](https://developer.unipile.com/v2.0/reference/api-usage)
- [Dashboard](https://dashboardv2.unipile.com)
