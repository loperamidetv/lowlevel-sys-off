# Low-Level Systems & Offensive Security

A hands-on (personal!) journey into low-level systems and offensive security. This repository documents projects exploring process memory, reverse engineering, and kernel-level programming to build deep understanding of how computers really work.

## Motivation

This project represents my personal exploration of how computers really work. 
I am fascinated by low-level systems, reverse engineering, and understanding the inner workings of operating systems. 
It is not about building production software, but about learning by doing, experimenting, and creating small tools to explore memory, processes, and kernel mechanics.

## Roadmap

### 01-read-memory
- Explore Windows inter-process memory reading.
- Learn OpenProcess, ReadProcessMemory, and basic memory layout.

### 02-memory-scanner
- Scan process memory for patterns.
- Understand dynamic memory allocation and address offsets.

### 03-dll-injection
- Simple userland DLL injection.
- Hook basic Windows API functions.

### 04-reverse-engineering
- Analyze binaries using disassembly and debugging.
- Understand function calls, variables, and memory layout.

### 05-kernel-exploration
- Kernel-level programming, syscalls, and simple drivers.
- Explore protections and security mechanisms at the OS level.

## Skills & Tools

- Languages: C
- OS: Windows 10+, Linux (coming)
- Debuggers: x64dbg, GDB (Linux later)
- Concepts: memory layout, process handles, kernel-level programming, reverse engineering, ASLR, DEP

## How to use this repository

- Each project has its own folder under `projects/`.
- Refer to each project's README.md for compilation instructions, code structure, and usage examples.
- Notes, diagrams, and screenshots are in the `docs/` folder.
