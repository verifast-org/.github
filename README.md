# Verifast - Community Health Files

This repository contains the
default [community health files](https://help.github.com/en/github/building-a-strong-community/creating-a-default-community-health-file)
for the [`VeriFast`](https://github.com/verifast-org) organization.

## Renovate preset

`default.json` is the organization's Renovate preset. It extends the shared coding standards and keeps this
organization's reusable workflows on their version tags. A repository uses it with:

```json
{
    "$schema": "https://docs.renovatebot.com/renovate-schema.json",
    "extends": ["github>verifast-org/.github"]
}
```
