# Home Assistant Add-on: Healthchecks

[![Release][release-shield]][release] ![Project Stage][project-stage-shield] ![Project Maintenance][maintenance-shield]

Self-hosted cron job and background task monitoring

## About

[Healthchecks][healthchecks] watches your cron jobs, backups and background
tasks. Each job gets a URL to request when it finishes; if the request does not
arrive on schedule, Healthchecks notifies you over email, Apprise, a webhook,
or any of its other integrations.

The add-on serves the web interface twice: through the Home Assistant sidebar
panel, and on a mapped port that your monitored machines send their pings to.

[:books: Read the full add-on documentation][docs]

## Installation

Add this repository to your Home Assistant instance and install the
Healthchecks add-on from the add-on store.

[docs]: https://github.com/shawly/hassio-app-healthchecks/blob/v1.0.0/healthchecks/DOCS.md
[healthchecks]: https://github.com/healthchecks/healthchecks
[maintenance-shield]: https://img.shields.io/maintenance/yes/2026.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[release-shield]: https://img.shields.io/badge/version-v1.0.0-blue.svg
[release]: https://github.com/shawly/hassio-app-healthchecks/tree/v1.0.0