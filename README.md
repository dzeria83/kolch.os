# KOLCH OS

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Zig](https://img.shields.io/badge/Zig-0.11.0-orange)](https://ziglang.org)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)]()

KOLCH OS (Kryptographically Optimized Lightweight Core Hierarchy) – A mathematically robust,
self-healing operating system based on sharding and Galois fields

## მახასიათებლები
- HyperTerminal 300+ By order
- KTIS – sharded trace system
- Reed-Solomon Correction
- Isabelle-ს Formal verification
- Multi-level access control (User, SU)

- ## 📸 HyperTerminal Demo

![KOLCH OS HyperTerminal](https://github.com/dzeria83/kolch.os/raw/main/assets/terminal-demo.jpg)

## ლიცენზია
KOLCH OS is licensed under the Apache License, Version 2.0. See [LICENSE](LICENSE) for details.

## აწყობა და გაშვება
1. დააყენეთ Zig 0.11.0 ან უფრო ახალი
2. გაუშვით:
   ```bash
   zig build
   qemu-system-x86_64 -kernel zig-out/bin/kolch_kernel
