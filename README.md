# Portfolio / Resume

Source code and documentation for my professional profile.

## 📄 Access
- [View latest PDF version](./CV-QUENTIN-STOLL.pdf)
- [View raw LaTeX source](./src/)

## 🏗 About
I am an Epitech Tech 4 student specializing in **Systems and Software Architecture**. 
My focus is on low-level optimization, distributed systems, and robust software design. 
This repository demonstrates my commitment to automation, version control, and clean technical documentation.

## 🚀 Selected Technical Projects

### R-Type (Network & ECS Architecture)
* **Purpose:** Development of a high-performance, multiplayer arcade game engine.
* **Architecture:** Implemented an **Entity-Component-System (ECS)** pattern to ensure decoupled logic and high scalability.
* **System/Networking:** Built a robust custom network protocol over **UDP** to handle real-time synchronization, packet loss, and latency compensation.
* **Key Tech:** C++, Multithreading, Socket Programming, ECS.

### Glados (Compiler Design & Functional Programming)
* **Purpose:** Design and implementation of a custom language compiler.
* **Architecture:** Developed the full pipeline: Lexical analysis, Parsing (AST generation), and Code generation.
* **System/Engineering:** Deep dive into formal grammars, recursive descent parsing, and functional paradigms to ensure memory safety and efficient type checking.
* **Key Tech:** Haskell, Compiler Design, Functional Programming, AST.

### 42sh (Shell & OS Interaction)
* **Purpose:** Development of a robust UNIX-like shell from scratch.
* **Architecture:** Implemented a complex Command Line Parser, job control, and signal handling.
* **System/Engineering:** Deep dive into process lifecycle management (`fork`, `exec`, `wait`), pipe redirection, and environment variable manipulation.
* **Key Tech:** C, POSIX APIs, Process Control, File Descriptors.

### Arcade (Modular Software Architecture)
* **Purpose:** Design of a modular, cross-platform game engine capable of dynamically loading libraries.
* **Architecture:** Implemented a **Plugin-based architecture** using dynamic linking (`dlopen`, `dlsym`) to switch between different graphics (SFML/NCurses) and game engines at runtime.
* **System/Engineering:** Focus on decoupling interfaces from implementations to ensure high modularity and maintainability.
* **Key Tech:** C++, Dynamic Linking, Design Patterns (Factory, Singleton), Abstraction.

### MyTeams (Network & Distributed Systems)
* **Purpose:** Implementation of a multi-user communication server using a custom protocol.
* **Architecture:** Designed a server-side state machine to manage user authentication, channel management, and thread-safe data access.
* **System/Networking:** Built a reliable TCP-based server capable of handling multiple concurrent clients using `select` or `epoll` for multiplexing I/O.
* **Key Tech:** C, TCP Sockets, Multiplexing, Thread Safety, Protocol Design.

### MiniLibC (Low-Level Systems & ASM)
* **Purpose:** Re-implementation of the standard C library using assembly.
* **Architecture:** Direct interaction with the system interface; mastering the **calling conventions** ($x86\_64$ ABI) and stack frame management.
* **System/Engineering:** Focused on performance optimization and hardware-level execution logic.
* **Key Tech:** Assembly (NASM), $x86\_64$ ABI, System Calls, Linker/Loader.
## ⚙️ Build Process
This document is automatically generated from LaTeX source files using a CI/CD pipeline. 

To build locally:
```bash
make all
