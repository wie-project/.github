# WIE Project (Wie Is Emulator)

An open-source research and engineering organisation focused on low-level emulation, systems programming, and high-performance cross-OS runtime environments.

## Our Projects

### 1. Kakehashi
**A lightweight, blazing fast userspace translator to run macOS ARM64 binaries on Linux ARM.**
* **The Core Idea:** Complete rejection of kernel modules (LKM) in favour of a pure userspace runtime. It uses a fast assembly hypercall bridge to route Mach-O system calls directly into a host Rust environment with identity-mapped memory.
* **Tech Stack:** Rust, Assembly (ARM64).

### 2. WIE — Wie Is Emulator
**An experimental PE64 userspace emulator written in Rust.**
* **The Core Idea:** Designed to run Windows x64 binaries seamlessly on Apple Silicon macOS via JIT emulation. 
* **Tech Stack:** Rust, JIT.

---

## The Team
* **@Vladislav-Kalinkin** — Founder & Lead Systems Engineer
* **@DevYatsu** — Co-developer (WIE)

## License
Our projects are distributed under open-source licenses (**Apache-2.0** for Kakehashi, **LGPL-3.0** for WIE).
