# Theatron extension registry

The Theatron extension registry is a public index of community extensions, including integrations with other Minecraft plugins. Publishers maintain their extension source and releases in their own repositories; this repository holds listing metadata.

> **Availability:** This repository currently contains a README only. There is no listing schema, submission process, or published index yet.

## How listings work

A listing pull request identifies the publisher, source, license, compatible Theatron and Paper versions, dependencies, release URL, and immutable artifact digest. Automated checks and maintainer review precede inclusion in the catalog used by the Theatron panel.

A listing will mean the metadata passed the registry's checks; it will not be a security guarantee. Operators will review and approve installation. Self-hosted instances will also be able to install locally built or unlisted extensions, so this registry will be optional.

Paid content and its licensing service belong to Apeyron Central, outside this community registry. The registry itself will not process payments or host commercial binaries.

## Related repositories

- [Theatron core](https://github.com/theatronmc/theatron) — engine, panel, Paper runtime, and public extension contracts.
- [Extension template](https://github.com/theatronmc/extension-template) — Kotlin starter for extension authors.
