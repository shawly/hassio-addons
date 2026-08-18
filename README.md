# shawly's Home Assistant Apps

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## About

A private Home Assistant app repository, holding the apps I run myself.

The structure and tooling follow the
[Home Assistant Community Apps][community-apps] repository, so apps here are built,
published and updated the same way. Every app directory is generated from that app's own
repository on release; `.apps.yml` lists where each one lives.

## Apps in this repository

### &#10003; [Healthchecks][app-healthchecks]

![Latest Version][healthchecks-version-shield]
![Supports aarch64 Architecture][healthchecks-aarch64-shield]
![Supports amd64 Architecture][healthchecks-amd64-shield]

Self-hosted cron job and background task monitoring

[:books: Healthchecks documentation][app-doc-healthchecks]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of `MAJOR.MINOR.PATCH`. In a nutshell, the version will be incremented
based on the following:

- `MAJOR`: Incompatible or major changes.
- `MINOR`: Backwards-compatible new features and enhancements.
- `PATCH`: Backwards-compatible bugfixes and package updates.

## License

MIT License. See [LICENSE.md](LICENSE.md).

[app-healthchecks]: https://github.com/shawly/hassio-app-healthchecks/tree/v1.0.0
[app-doc-healthchecks]: https://github.com/shawly/hassio-app-healthchecks/blob/v1.0.0/README.md
[healthchecks-version-shield]: https://img.shields.io/badge/version-v1.0.0-blue.svg
[healthchecks-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[healthchecks-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[community-apps]: https://github.com/hassio-addons/repository
[license-shield]: https://img.shields.io/github/license/shawly/hassio-addons.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2026.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[semver]: http://semver.org/spec/v2.0.0.html