**English** | [简体中文](Home-zh-CN)

# TWOTP1 Virtual Base System — Wiki Home

Welcome to the official documentation wiki for **TWOTP1 Virtual Base System (TWOTP1-System)**.

---

## Quick Facts

| Item | Detail |
|------|--------|
| Software name | TWOTP1 Virtual Base System |
| Developer | Wang Ji (王骥, GitHub: [xirifengjing](https://github.com/xirifengjing)) |
| Current version | **V1.1** (released 2026-11-09) |
| Initial version | V1.0 (released 2026-11-08) |
| Development tool | Scratch (graphical programming) |
| Packaging tool | TurboWarp Packager (single-file HTML) |
| Software type | Lightweight innovative virtual runtime system |
| Repository | [TWOTP1-System](https://github.com/xirifengjing/TWOTP1-System) |

---

## What is TWOTP1?

TWOTP1 (Virtual Base System) is a lightweight, innovative virtual runtime system. Users do not need to install any system image — the software ships with a natively designed virtual runtime environment and works out of the box on any device that can run a modern browser.

The system uses a built-in automatic restore engine. Every time the program is closed and restarted, all temporary runtime data is cleared automatically, and only content the user has actively saved to the persistent file system is retained — keeping the system clean and residue-free while still protecting user files.

## Core Features

- **Single file, zero dependencies** — developed with Scratch graphical programming and packaged by TurboWarp Packager into a standalone HTML file. Just double-click it in any modern browser; no extra software or runtime is required.
- **Dual-layer storage architecture** — the temporary runtime environment is isolated from the persistent user file system, so files you intentionally save are not lost after a restart.
- **Automatic restore mechanism** — temporary runtime data is cleared on every restart, so the system always returns to a clean, smooth initial state.
- **Full platform compatibility** — runs on Windows, macOS, Linux desktops, as well as tablets and phones — any device with a modern browser.

---

## How to Use

1. Download `TWOTP1 虚拟基层系统 程序.html` from the [repository](https://github.com/xirifengjing/TWOTP1-System) to your local machine.
2. Open the HTML file with any modern browser (Chrome/Edge 100+, Firefox 99+, Safari 15+ are recommended). The system starts immediately — no installation needed.
3. Notes while using:
   - Temporary caches and application data generated at runtime are automatically cleared after a restart.
   - To keep your own files, save them into the built-in **persistent file system**; they will persist across restarts.

---

## Version History

### V1.1 — Latest stable release (2026-11-09)

This release focuses on system stability and feature refinement:

1. **Updated built-in browser module** — improved kernel compatibility and page-loading behaviour, fixed page rendering and unresponsive issues in some environments, and improved stability when running across devices.
2. **Updated fatal error green screen** — reworked the full-screen prompt displayed when the system encounters an unrecoverable fatal error.
   - **Why green?** Green is used as the main colour because green is the author's lucky colour; it also stays highly recognisable across different displays.
   - **Why the Microsoft `:(` face?** The sad face uses the Microsoft-style `:(` ASCII character instead of a custom emoji, in order to avoid character misalignment and rendering errors on different devices and under different encodings.
3. **Updated virtual machine status page** — a dedicated system status page presents core VM parameters such as memory usage, uptime and storage status in a clearer, more organised layout.
4. **Updated system restart function** — the restart flow has been optimised so that temporary data is cleared completely and persistent files are safely preserved, fixing restart failures and incomplete restores in some cases.

### V1.0 — Initial release (2026-11-08)

The first official release, laying the core foundation:

- Native virtual runtime environment core
- Basic persistent file system for user-stored files
- Automatic restore engine (basic capability)
- Single-file HTML packaging with cross-device compatibility verified
- Program demo video plus an original-work timestamp certificate

---

## License & Copyright

Copyright (c) 2026 Wang Ji (王骥). All rights reserved. This software is protected by the Copyright Law of the People's Republic of China and applicable international copyright treaties.

- ✅ **Permitted without additional permission**: Free download, local running and normal use of the full functionality of this software for personal, non-commercial purposes.
- ❌ **Not permitted without prior written permission**: Copying, distributing or transmitting the software (or any part of it) in any form — including uploading to third-party download platforms, repackaging and sharing, or mirroring it; reverse engineering, decompiling, disassembling, modifying, tampering with, recreating or developing derivative works; and any commercial use, including selling, renting, charging for related services, or embedding it in commercial products or profit-making projects.

> ⚠️ **Special notice**: Viewing the source code in this repository or browsing the project page does not grant any license or right to copy, modify, distribute or otherwise exploit this software beyond the permitted scope stated above.

- Full English license: see [LICENSE](https://github.com/xirifengjing/TWOTP1-System/blob/main/LICENSE) in the repository
- 中文许可协议：see [LICENSE.zh-CN](https://github.com/xirifengjing/TWOTP1-System/blob/main/LICENSE.zh-CN)
- Full changelog: see [CHANGELOG.md](https://github.com/xirifengjing/TWOTP1-System/blob/main/CHANGELOG.md) in the repository

### Copyright notice

This software was independently developed by the author Wang Ji, with no plagiarism, misappropriation, commissioned development or work-for-hire involved. The author is the sole original copyright holder of this software and legally enjoys complete copyright.

---

## Navigation

- [Project Repository](https://github.com/xirifengjing/TWOTP1-System)
- [简体中文 Wiki](Home-zh-CN)