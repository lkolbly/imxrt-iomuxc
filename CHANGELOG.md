# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased]

### Changed

- **BREAKING** rename feature flags and module: `"imxrt106x" => "imxrt1060"`

  For rational on this change, see
  [here](https://github.com/imxrt-rs/imxrt-rs/pull/91).

### Added

- i.MX RT 1010 support with the `"imxrt1010"` feature:
  - I2C
  - SPI
  - UART

## [0.1.2] - 2020-11-23

### Added

- Support for ADC pins

## [0.1.1] - 2020-09-10

### Added

- Export a `prelude` module to help others re-export APIs that are not specific
  to a crate.

## [0.1.0] - 2020-08-28

First release

- Configuration API
- Preliminary support for i.MX RT 1060 chips:
  - I2C
  - GPIO
  - PWM
  - SPI
  - UART

[Unreleased]: https://github.com/imxrt-rs/imxrt-iomuxc/compare/v0.1.2...HEAD
[0.1.2]: https://github.com/imxrt-rs/imxrt-iomuxc/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/imxrt-rs/imxrt-iomuxc/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/imxrt-rs/imxrt-iomuxc/releases/tag/v0.1.0