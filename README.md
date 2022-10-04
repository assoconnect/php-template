# Title

[![Build Status](https://github.com/assoconnect/your-repo/actions/workflows/build.yml/badge.svg)](https://github.com/assoconnect/your-repo/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=assoconnect_your-repo&metric=alert_status)](https://sonarcloud.io/dashboard?id=assoconnect_your-repo)

## Installation

```
composer require assoconnect/your-repo
```

## How-to

* Update the current README replacing `your-repo` with the real name of your repo
* Update the [build.yml](.github/workflows/build.yml) file replacing `your-repo` with the real name of your repo
* Update the [composer.json](./composer.json) file replacing `your-repo` with the real name of your repo, and the PSR setting. Add also a description and some keywords
* Keep the relevant `phpunit.xml.dist` file and rename it to `phpunit.xml.dist`
* Add the repository to the [App Developers Team](https://github.com/orgs/assoconnect/teams/app-developpers/repositories) and make the team admin
* Create a project at [SonarCloud](https://sonarcloud.io/projects/create) under the AssoConnect organization with `assoconnect_your-repo` as key and `your-repo` as display name
* Don't configure the SonarCloud project as the SonarCloud token is already stored at the organization level at Github
* Code must be placed in `src`
* Tests must be placed in `tests`
* Publish it at [Packagist](https://packagist.org/packages/submit)
* Write a relevant README
* Remove this how-to section of the README
