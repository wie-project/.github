<div align="center">

# 🚀 WIE (Wie Is Emulator)

**An experimental PE64 userspace emulator written in Rust.**  
*Specifically tailored for running Windows binaries seamlessly on Apple Silicon macOS.*

[![Rust CI](https://img.shields.io/github/actions/workflow/status/wie-project/wie/ci.yml?branch=main)](https://github.com/wie-project/wie/actions)
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)
[![Rust](https://img.shields.io/badge/rust-1.97%2B-orange.svg)](https://www.rust-lang.org)

</div>

---

### 🛠️ Architecture & Components
The codebase is modularized into independent crates to ensure clean architecture and fast build times:
* **`wie-cpu`** — The core CPU emulation engine.
* **`wie-winapi`** — Windows API emulation layer interfaces.
* **`wie-pe`** — Portable Executable format parser for PE64 files.
* **`wie-cli`** — Command-line interface to control and run the binaries.

### 👥 The Team
* **[@Vladislav-Kalinkin](https://github.com)** — Lead Developer & Founder
* **[@DevYatsu](https://github.com)** — Co-developer

### 💬 Community & Support
* Found a crash or an unhandled Windows API? Open a **[Bug Issue](https://github.com)**.
* Want to discuss emulation ideas or ask questions? Join our **[Discussions](https://github.com)**!

### 📜 License
This project is open-source and distributed under the **LGPL-3.0 License**.
