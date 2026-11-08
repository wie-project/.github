# WIE Project

An open-source research and engineering organisation focused on low-level emulation, systems programming, and high-performance cross-OS runtime environments.

## Our Projects

### 1. PS4Recomp
**An experimental Experimental macOS Apple Silicon static recompiler for PS4 games.**
* **The Core Idea:** Creating native game ports for Apple Silicon without using Rosetta 2, JIT and MoltenVK
* **Tech Stack:** Go, C/C++, Objective-C/C++.
  
### 2. Kakehashi
**An experimental lightweight userspace translator to run macOS ARM64 binaries on Linux ARM.**
* **The Core Idea:** Complete rejection of kernel modules (LKM) in favour of a pure userspace runtime. It uses a fast assembly hypercall bridge to route Mach-O system calls directly into a host Rust environment with identity-mapped memory.
* **Tech Stack:** Rust, Assembly (ARM64).

### 3. WIE — Wie Is Emulator
**An experimental PE64 userspace emulator written in Rust.**
* **The Core Idea:** Designed to run Windows x64 binaries seamlessly on Apple Silicon macOS via JIT emulation. 
* **Tech Stack:** Rust, JIT.

---

## The Team
* **@Vladislav-Kalinkin** — Founder
* **@DevYatsu** — Co-developer (WIE)

## License
Our projects are distributed under open-source licenses (**GPL-2.0** for PS4Recomp, **Apache-2.0** for Kakehashi, **LGPL-3.0** for WIE).
