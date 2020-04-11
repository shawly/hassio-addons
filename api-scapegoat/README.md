# API Scapegoat Hass.io Add-on

[![Release][release-shield]][release] ![Project Stage][project-stage-shield] ![Project Maintenance][maintenance-shield]

<img src="logo.png" height="256">

API gateway for offline APIs. Safely power off your devices without getting your Home-Assistant logs full of spam because of unreachable hosts!

## About

I created this add-on because there are devices which lose their network capability when they are turned off and I got tired of my REST sensors to spam my logs.

With this add-on you can

- a proxy for every API in your home
- return a custom response when the target host is unreachable

A good example for this would be my TV, it's connected to a master-slave power strip which turns on or off depending on the power consumption of my AVR.  
This means that when my AVR is in standby, my TV's power is fully cut off, meaning it's API can't be accessed anymore so my sensors will log errors until the TV has it's power back.

With API Scapegoat I can now create a proxy to my TV's API, returning a default response for when it becomes unreachable.  
I simply return the same API response for when my TV is in standby.

```json
{ 
  "error": [7, "not power-on"], 
  "id": 40 
}
```

[Click here for the full documentation][docs]

[docs]: https://github.com/shawly/hassio-api-scapegoat/blob/v1.0.0/README.md
[maintenance-shield]: https://img.shields.io/maintenance/yes/2020.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-wip-orange.svg
[release-shield]: https://img.shields.io/badge/version-v1.0.0-blue.svg
[release]: https://github.com/shawly/hassio-api-scapegoat/tree/v1.0.0