# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased](https://github.com/elastic/integrations-registry/compare/v0.1.0...master)

### Breaking changes

### Bugfixes

* Change empty /search API output from `null` to `[]`. [#111](https://github.com/elastic/integrations-registry/pull/111)

### Added

* Add validation check that Kibana min/max are valid semver versions. [#99](https://github.com/elastic/integrations-registry/pull/99)
* Adding Cache-Control max-age headers to all http responses set to 1h. [#101](https://github.com/elastic/integrations-registry/pull/101)
* Validate packages to guarantee only predefined categories can be used. [#100](https://github.com/elastic/integrations-registry/pull/100)
* Cache all manifest on service startup for resource optimisation. [#103](https://github.com/elastic/integrations-registry/pull/103)
* Fix Docker image to specific Golang version. [#107](https://github.com/elastic/integrations-registry/pull/107)
* Add .dockerignore file for slimmer image. [#104](https://github.com/elastic/integrations-registry/pull/104)
* Move package generation to its own package. [#112](https://github.com/elastic/integrations-registry/pull/112)
* Remove not needed files in Docker image. [#106](https://github.com/elastic/integrations-registry/pull/106)

### Deprecated

### Known Issue

## [0.1.0]

First tagged release. No changelog existed so far.
