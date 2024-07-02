# PositionPal custom Renovate configuration

This repository contains a custom Renovate configuration for PositionPal organization repositories.

To use this configuration, just add a `renovate.json` file to the root of your repository with the following content:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>position-pal/renovate-config"
  ]
}
```

Useful links:
- [Shareable config presets](https://docs.renovatebot.com/config-presets/#shareable-config-presets)
- [Renovate documentation](https://docs.renovatebot.com/)
