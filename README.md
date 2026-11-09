**English** | [简体中文](README.zh-CN.md)

# TWOTP1 Virtual Base System

> **Latest Version**: V1.1 | **Developer**: Wang Ji (王骥) | **Initial Release**: 2026-11-08 | **V1.1 Release**: 2026-11-09

## Basic Information

- **Software Name**: TWOTP1 Virtual Base System
- **Developer**: Wang Ji (王骥)
- **Current Version**: V1.1 (released 2026-11-09)
- **Initial Version**: V1.0 (released 2026-11-08)
- **Development Tool**: Scratch (graphics programming)
- **Packaging Tool**: TurboWarp Packager (single-file HTML output)
- **Software Type**: Lightweight innovative virtual runtime system

## Project Overview

TWOTP1 (Virtual Base System) is a lightweight innovative virtual runtime system. It requires no system image to be installed by the user: it ships with a natively designed virtual runtime environment and works out of the box on any device that can run a modern browser.

Reboot behaviour is handled by a built-in automatic restore engine. Every time the program is closed and restarted, all temporary runtime data is cleared automatically, and only the content the user has actively saved into the persistent file system is retained — clean and residue-free, while user files are still protected.

## Core Features

- **Single file, no dependencies**: developed with Scratch graphics programming and packaged by TurboWarp Packager into a standalone HTML file. Just double-click it in any modern browser — no extra software or runtime to install.
- **Two-layer storage architecture**: the temporary runtime environment is isolated from the persistent user file system, so files you save on purpose are not lost after a restart.
- **Automatic restore mechanism**: temporary runtime data is cleared on restart, so the system always returns to its clean, smooth initial state.
- **Full platform compatibility**: runs on Windows, macOS and Linux desktops, as well as tablets and phones — any device with a browser.

## Version History

### V1.1 — Latest stable release (2026-11-09)

This release focuses on system stability and feature refinement:

1. **Built-in browser module updated** — improved kernel compatibility and page-loading behaviour, fixed page rendering and unresponsive issues in some environments, and improved stability when running across devices.
2. **Fatal error green screen updated** — the full-screen prompt shown when the system hits an unrecoverable fatal error has been reworked.
   - *Design note*: green is used as the main colour because green is the author's lucky colour.
   - *Design note*: the sad face uses the Microsoft-style `:(` character instead of a custom emoji, in order to avoid character misalignment on different devices and under different encodings.
3. **Virtual machine status page updated** — a dedicated system status page now presents core VM parameters such as memory usage, uptime and storage status in a clearer layout.
4. **System restart function updated** — the restart flow has been optimised so that temporary data is cleared completely and persistent files are safely preserved, fixing restart failures and incomplete restores in some cases.

### V1.0 — Initial release (2026-11-08)

The first official release, providing the core foundation:

- Native virtual runtime environment core
- Basic persistent file system for user-stored files
- Automatic restore engine (basic capability)
- Single-file HTML packaging with cross-device compatibility verified
- Demo video plus an original-work timestamp certificate

## Usage

1. Download `TWOTP1 虚拟基层系统 程序.html` from the repository Release page or the code directory to your local machine.
2. Open the HTML file with any modern browser (Chrome/Edge 100+, Firefox 99+, Safari 15+ recommended) to start the system. No installation is needed.
3. Notes while using it:
   - Temporary caches and application data generated at runtime are cleared automatically after a restart.
   - To keep your own files, save them into the built-in **persistent file system**; they will survive a restart.

## License

Copyright (c) 2026 Wang Ji (王骥, GitHub: xirifengjing). All rights reserved. This software is protected by the Copyright Law of the People's Republic of China and applicable international copyright treaties.

- ✅ **Permitted without further permission**: free download, local running and normal use of the full functionality of this software for personal, non-commercial purposes.
- ❌ **Not permitted without prior written permission**: copying, distributing or transmitting the software (or any part of it) in any form — including uploading it to third-party download platforms, repackaging and sharing it, or mirroring it; reverse engineering, decompiling, disassembling, modifying, tampering with, recreating or developing derivative works from the software; and any commercial use, including selling, renting, charging for related services, or embedding it in commercial products or profit-making projects.

> ⚠️ Special notice: viewing the source code in this repository or browsing the project page does not grant any license or right to copy, modify, distribute or otherwise exploit this software beyond the permitted scope stated above.

- Full English license: [LICENSE](LICENSE)
- 中文许可协议：[LICENSE.zh-CN](LICENSE.zh-CN)
- Full change log: [CHANGELOG.md](CHANGELOG.md)

## Copyright Notice

This software was independently developed by the author Wang Ji, with no plagiarism, misappropriation, commissioned development or work-for-hire involved. The author is the sole original copyright holder of this software and legally enjoys the complete copyright.