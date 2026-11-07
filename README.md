# VizHub documentation notes

This public repository contains an **older feature overview** for VizHub. It is not the source code for the current hosted application, and its earlier README mixed documented capabilities with assumptions about routes, integrations, downloads, and deployment.

## Where to start

- **Using VizHub:** [vizhub.com](https://vizhub.com/) is the current product entry point.
- **Historical feature ideas:** [HISTORICAL_FEATURE_OVERVIEW.md](HISTORICAL_FEATURE_OVERVIEW.md) preserves the earlier feature overview, explicitly marked **unverified**. Its instructions must not be used as a current runbook without independently checking each feature.
- **Public ecosystem repositories:** See the [VizHub GitHub organization](https://github.com/vizhub-studio) and its [public repository catalog](https://github.com/vizhub-studio/.github/blob/main/REPOSITORY_CATALOG.md).

## Maintenance policy

Documentation of current behavior should be verified against the application source and actual deployed user experience. In particular:

- **Identity and domains:** The current product is called **VizHub**. Legacy services and earlier UI screenshots must be labeled historical.
- **Features:** Check whether a capability exists, is enabled for a given plan, and is available in production before describing it as supported.
- **Pricing, auth, privacy and access controls:** These are time-sensitive; do not infer them from older notes.
- **Examples and links:** Use only confirmed URLs, scripts, and installation steps; mark unverified workflows as historical.
- **Security:** Do not publish private repository content, credentials, or customer data here.

This repository has no root `package.json` or build/test command. No live product behavior is changed by edits here.
