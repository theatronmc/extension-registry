# Theatron extension registry

This repository will be the public, pull-request-reviewed index of community Theatron extensions and integrations with other Minecraft plugins.

> **Status — registry workflow in preparation.** This repository currently contains documentation only. There is no listing schema, automated validation, published index, or submission process yet. Please do not submit extension listings until those are available.

## Intended model

Extension publishers will own their source and releases. A listing PR will identify the publisher, source, license, compatible Theatron and Paper versions, dependencies, release URL, and immutable artifact digest. Automated checks and maintainer review will precede inclusion in a generated catalog consumed by the Theatron panel.

A listing will mean the metadata passed the registry's checks; it will not be a security guarantee. Operators will review and approve installation. Self-hosted instances will also be able to install locally built or unlisted extensions, so this registry will be optional.

Paid content and its licensing service belong to Apeyron Central, outside this community registry. The registry itself will not process payments or host commercial binaries.

## Related repositories

- [Theatron core](https://github.com/theatronmc/theatron) — engine, panel, Paper runtime, and public extension contracts.
- [Extension template](https://github.com/theatronmc/extension-template) — future runnable starter for extension authors.

The first usable registry release will publish the schema, review policy, validation workflow, and installation guidance.
