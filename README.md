# Renovate config
Renovate configuration presets used in Telemark.

## Use this config in repositories
Create/update `renovate.json` in your repo with this configuration:
```JSON
{
  "extends": ["github>telemark/renovate-config"]
}
```

Or you can add a renovate section in the `package.json` file:
```JSON
{
  "name": "example-package",
  "description": "example-package desc",
  "version": "1.0.0",
  ...
  "renovate": {
    "extends": ["github>telemark/renovate-config"]
  },
  ...
}
```
