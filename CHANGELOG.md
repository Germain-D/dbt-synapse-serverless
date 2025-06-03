# Changelog

## Version 1.9.0 (2025-01-03)

### Added
- Support for dbt-core 1.9.x versions

### Fixed
- Fixed `ValueError: mutable default <class 'dbt.adapters.synapseserverless.relation.SynapseServerlessIncludePolicy'> for field include_policy is not allowed: use default_factory` error by using `field(default_factory=...)` instead of direct class instantiation
- Updated dependency requirements to use `dbt-synapse~=1.9.0`

### Changed
- Updated version from 1.4.0 to 1.9.0 to match dbt-core compatibility
- Updated setup.py to require dbt version 1.9

### Breaking Changes
- Minimum required dbt version is now 1.9.0

## Previous Versions

### Version 1.4.0
- Initial support for dbt-core 1.4.x
- Basic Synapse Serverless adapter functionality 