# GitHub Action for setting up Touca CLI

Plugin that installs and configures Touca CLI for use in subsequent steps.

## Example usage

```yaml
uses: trytouca/actions-setup-touca@v1
with:
  api_key: ${{ secrets.TOUCA_API_KEY }}
  api_url: https://api.touca.io/@/my-team
```

## Inputs

### `api_key`

**Optional** API Key for Touca Cloud/Enterprise instance to set in your Touca
configuration profile.

### `api_url`

**Optional** API URL of Touca Cloud/Enterprise instance to set in your Touca
configuration profile.
