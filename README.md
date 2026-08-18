# shawly's Home Assistant Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## About

A Home Assistant add-on repository for my personal add-ons. Feel free to try them out,
though they may be work in progress or tailored to my own setup.

The structure and tooling follow the
[Home Assistant Community Add-ons][community-addons] repository, so add-ons here are
built, published and updated the same way.

## Installation

In the Home Assistant add-on store, a possibility to add a repository is provided.
Use the following URL to add this repository:

```txt
https://github.com/shawly/hassio-addons
```

## Add-ons provided by this repository

### &#10003; [API Scapegoat][addon-api-scapegoat]

![Latest Version][api-scapegoat-version-shield]
![Supports aarch64 Architecture][api-scapegoat-aarch64-shield]
![Supports amd64 Architecture][api-scapegoat-amd64-shield]
![Supports armhf Architecture][api-scapegoat-armhf-shield]
![Supports armv7 Architecture][api-scapegoat-armv7-shield]
![Supports i386 Architecture][api-scapegoat-i386-shield]

API gateway with failover for REST sensors.

[:books: API Scapegoat add-on documentation][addon-doc-api-scapegoat]

### &#10003; [Healthchecks][addon-healthchecks]

![Latest Version][healthchecks-version-shield]
![Supports aarch64 Architecture][healthchecks-aarch64-shield]
![Supports amd64 Architecture][healthchecks-amd64-shield]

Self-hosted cron job and background task monitoring.

[:books: Healthchecks add-on documentation][addon-doc-healthchecks]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of `MAJOR.MINOR.PATCH`. In a nutshell, the version will be incremented
based on the following:

- `MAJOR`: Incompatible or major changes.
- `MINOR`: Backwards-compatible new features and enhancements.
- `PATCH`: Backwards-compatible bugfixes and package updates.

## Support

Every add-on lives in its own repository, and that is where its issues belong:

- [Open an issue for the add-on: API Scapegoat][api-scapegoat-issue]
- [Open an issue for the add-on: Healthchecks][healthchecks-issue]

For an issue with this repository itself, or to suggest a new add-on,
[open an issue here][issue].

## License

MIT License. See [LICENSE.md](LICENSE.md).

[addon-api-scapegoat]: https://github.com/shawly/hassio-api-scapegoat/tree/v1.0.0
[addon-doc-api-scapegoat]: https://github.com/shawly/hassio-api-scapegoat/blob/v1.0.0/README.md
[api-scapegoat-issue]: https://github.com/shawly/hassio-api-scapegoat/issues
[api-scapegoat-version-shield]: https://img.shields.io/badge/version-v1.0.0-blue.svg
[api-scapegoat-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[api-scapegoat-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[api-scapegoat-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[api-scapegoat-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[api-scapegoat-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[addon-healthchecks]: https://github.com/shawly/hassio-app-healthchecks/tree/v1.0.0
[addon-doc-healthchecks]: https://github.com/shawly/hassio-app-healthchecks/blob/v1.0.0/README.md
[healthchecks-issue]: https://github.com/shawly/hassio-app-healthchecks/issues
[healthchecks-version-shield]: https://img.shields.io/badge/version-v1.0.0-blue.svg
[healthchecks-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[healthchecks-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[community-addons]: https://github.com/hassio-addons/repository
[issue]: https://github.com/shawly/hassio-addons/issues
[license-shield]: https://img.shields.io/github/license/shawly/hassio-addons.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2026.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[semver]: http://semver.org/spec/v2.0.0.html