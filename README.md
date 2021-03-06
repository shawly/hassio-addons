# shawly's Hass.io Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![GitLab CI][gitlabci-shield]][gitlabci]

## About

A Hass.io addon repository for my personal add-ons. Feel free
to try them out, they might be WIP or tailored to my personal
needs though.

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/shawly/hassio-addons
```

## Add-ons provided by this repository

### &#10003; [API Scapegoat][addon-apiscapegoat]

![Latest Version][apiscapegoat-version-shield]
![Supports armhf Architecture][apiscapegoat-armhf-shield]
![Supports armv7 Architecture][apiscapegoat-armv7-shield]
![Supports aarch64 Architecture][apiscapegoat-aarch64-shield]
![Supports amd64 Architecture][apiscapegoat-amd64-shield]
![Supports i386 Architecture][apiscapegoat-i386-shield]
![Docker Pulls][apiscapegoat-pulls-shield]

API gateway with failover for REST sensors.

[:books: API Scapegoat add-on documentation][addon-doc-apiscapegoat]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

- [Open an issue for the add-on: API Scapegoat][apiscapegoat-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## License

MIT License

Copyright (c) 2020 shawly

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-apiscapegoat]: https://github.com/shawly/hassio-api-scapegoat/tree/v1.0.0
[addon-doc-apiscapegoat]: https://github.com/shawly/hassio-api-scapegoat/blob/v1.0.0/README.md
[apiscapegoat-issue]: https://github.com/shawly/hassio-api-scapegoat/issues
[apiscapegoat-version-shield]: https://img.shields.io/badge/version-v1.0.0-blue.svg
[apiscapegoat-pulls-shield]: https://img.shields.io/docker/pulls/hassiofun/api-scapegoat-armhf.svg
[apiscapegoat-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[apiscapegoat-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[apiscapegoat-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[apiscapegoat-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[apiscapegoat-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[shawly]: https://github.com/shawly
[gitlabci-shield]: https://gitlab.com/shawly/hassio-addons/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/shawly/hassio-addons/pipelines
[issue]: https://github.com/shawly/hassio-addons/issues
[license-shield]: https://img.shields.io/github/license/shawly/hassio-addons.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2020.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html
[third-party-addons]: https://home-assistant.io/hassio/installing_third_party_addons/