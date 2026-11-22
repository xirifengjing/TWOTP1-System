[简体中文](CHANGELOG.md) | **English**

# Changelog

All notable changes to the TWOTP1 Virtual Base System are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [v1.1] - 2026-11-09

This release focuses on system stability and feature refinement.

### Changed

- **Built-in browser module** — improved runtime compatibility and page-loading behaviour, fixed page rendering and unresponsive issues in some environments, and improved running stability across devices.
- **Fatal error green screen** — reworked the full-screen prompt displayed when the system hits an unrecoverable fatal error, so an abnormal state is easier to recognise.
  - The green screen uses green as its main colour because green is the author's lucky colour; green also stays highly recognisable on different displays.
  - The sad face uses the Microsoft-style `:(` character instead of a custom emoji, in order to avoid character misalignment and rendering errors on different devices and under different encodings.
- **Virtual machine status page** — upgraded the VM runtime status page and reworked its information layout, so core parameters such as memory usage, uptime, storage status and automatic-restore status are shown more clearly.
- **System restart function** — optimised the complete restart flow: restart is faster and more reliable, the automatic restore mechanism works more consistently, and temporary data is cleared more thoroughly. Restart failures and incomplete restores in some cases have been fixed.

### Fixed

- Fixed the abnormal page display and unresponsive behaviour of the built-in browser in some environments.
- Fixed restart failures and incomplete environment restores in some cases.

## [v1.0] - 2026-11-08

The first official release, providing the core foundation of the system.

### Added

- Native virtual runtime environment core.
- Basic persistent file system that lets users store files on purpose.
- Automatic restore engine (basic capability) that resets temporary runtime data on start-up.
- Single-file HTML packaging, with cross-device compatibility verified.
- Demo video of the program and an original-work timestamp certificate.
