# C++ Systems Mastery

This repository documents my long-term journey toward deep C++ programming mastery, with a focus on systems programming, memory management, data structures, performance, and compiler/runtime engineering foundations.

The purpose of this repository is not simply to learn C++ syntax. The goal is to build serious, recruiter-visible projects that demonstrate practical understanding of modern C++, object lifetime, RAII, templates, smart pointers, generic programming, concurrency, allocators, parsing, bytecode interpretation, and runtime design.

This repository is part of my broader preparation for a future career direction in compiler/runtime engineering. For now, the focus is on building strong foundations in C/C++, math, systems thinking, and clean engineering practice while continuing my PhD dissertation work.

---

## Repository Goal

The goal of this repository is to complete 17 progressively structured C++ projects.

Each project builds on the previous one:

1. Basic C++ fluency
2. Resource management
3. Object lifetime
4. Templates and generic programming
5. Smart pointers and ownership
6. Linear algebra and numerical programming
7. Data structures
8. Iterators and algorithms
9. Expression trees and symbolic computation
10. Parsing
11. CLI and configuration tooling
12. Logging, testing, and benchmarking
13. Multithreading and task scheduling
14. Memory allocation
15. Bytecode interpretation
16. Intermediate representation / code generation
17. Mini runtime system

By the end of this repository, I want to have a strong body of work showing that I understand C++ beyond surface-level programming.

---

## Project List

| # | Project | Focus Area | Status |
|---|---------|------------|--------|
| 01 | Modern C++ Basics Toolkit | Core C++ syntax, classes, STL basics | Not Started |
| 02 | RAII File Wrapper | Resource management, constructors/destructors | Not Started |
| 03 | Custom String Class | Rule of Three/Five, dynamic memory, move semantics | Not Started |
| 04 | Template Vector Class | Templates, generic containers, iterators | Not Started |
| 05 | Smart Pointer Library | Ownership, RAII, reference counting | Not Started |
| 06 | C++ Matrix and Linear Algebra Library | Templates, operators, numerical programming | Not Started |
| 07 | Generic Data Structures Library | Lists, stacks, queues, trees, graphs, hash maps | Not Started |
| 08 | Iterator and Algorithm Library | STL-style design, custom iterators, algorithms | Not Started |
| 09 | Expression Tree and Symbolic Algebra Engine | ASTs, expression modeling, symbolic computation | Not Started |
| 10 | JSON Parser in Modern C++ | Tokenization, parsing, recursive descent | Not Started |
| 11 | Configuration System and CLI Framework | Command-line tools, config files, typed options | Not Started |
| 12 | Logging, Benchmarking, and Testing Framework | Developer tooling, diagnostics, timing | Not Started |
| 13 | Multithreaded Task Scheduler | Threads, mutexes, condition variables, futures | Not Started |
| 14 | Memory Pool Allocator | Custom allocation, free lists, memory pools | Not Started |
| 15 | Bytecode Interpreter in Modern C++ | VM design, bytecode, stack execution | Not Started |
| 16 | JIT/IR Playground or LLVM IR Generator | IR design, code generation foundations | Not Started |
| 17 | Mini Runtime for a Small Language | Runtime design, execution model, memory model | Not Started |

---

## Project Structure

Each project will follow a clean structure whenever possible:

```text
project_name/
  README.md
  include/
  src/
  tests/
  examples/
  CMakeLists.txt
  notes.md