# Changelog

All notable changes to this project will be documented in this file.

The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Added support for [Customer Managed Encryption Keys](https://cloud.google.com/compute/docs/disks/customer-managed-encryption) in persistent disks attached to the instances.

### Changed

- Updated for Terraform 0.12. [#11]
- Updated tests and examples to Google provider 3.13.

### Fixed

- Avoid metadata conflicts after SAP startup script completes. [#11]

## [0.2.0] - 2019-09-10

### Added

- Submodule to deploy NetWeaver. [#2]

### Fixed

- Required VM instance service account roles added to the submodule READMEs. [#4]

## [0.1.0] - 2019-07-04

### Added

- Initial release

[Unreleased]: https://github.com/terraform-google-modules/terraform-google-sap/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/terraform-google-modules/terraform-google-sap/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/terraform-google-modules/terraform-google-sap/releases/tag/v0.1.0
[#2]: https://github.com/terraform-google-modules/terraform-google-sap/pull/2
[#4]: https://github.com/terraform-google-modules/terraform-google-sap/issues/4
[#11]: https://github.com/terraform-google-modules/terraform-google-sap/pull/11
