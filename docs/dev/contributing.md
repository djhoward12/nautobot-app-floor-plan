# Contributing to the App

The project is packaged with a light [development environment](dev_environment.md) based on `docker-compose` to help with the local development of the project and to run tests.

The project is following Network to Code software development guidelines and is leveraging the following:

- Python linting and formatting: `black`, `pylint`, `bandit`, `flake8`, and `pydocstyle`.
- YAML linting is done with `yamllint`.
- Django unit test to ensure the app is working properly.

Documentation is built using [mkdocs](https://www.mkdocs.org/). The [Docker based development environment](dev_environment.md#docker-development-environment) automatically starts a container hosting a live version of the documentation website on [http://localhost:8001](http://localhost:8001) that auto-refreshes when you make any changes to your local files.

## Branching Policy

Code contributions should be directed at the `develop` branch. This branch will be merged into `main` when a new release is ready for publication. The latest commit in `main` will always correspond to the latest release of this App.

## Release Policy

There is no set release schedule for this App. New releases will be published as appropriate when new features and/or bug fixes are ready.
