# Contributing

Everything in an app's directory in this repository is **generated**. The
[Repository Updater](https://github.com/hassio-addons/repository-updater) copies it in
from the app's own repository on every release, so changes made here are overwritten
on the next update.

To change an app, open a pull request against its repository. `.apps.yml` in the root
of this repository lists where each one lives.

Pull requests against this repository make sense for the repository itself: `.apps.yml`,
`.README.j2`, the workflows and the documentation.
