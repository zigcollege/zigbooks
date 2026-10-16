# Awesome Zig Books

> A curated list of books and resources for the [Zig programming language](https://ziglang.org).

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Contributions are always welcome — please read the [Contributing](#contributing) section first.

---

## Contents

- [Starter Books](#starter-books)
- [Advanced Books](#advanced-books)
- [Systems, Networking & Embedded](#systems-networking--embedded)
- [Free & Online Resources](#free--online-resources)
- [Interactive & Video](#interactive--video)
- [Community & Links](#community--links)

---

## Starter Books

### [Introduction to Zig: A Project-Based Book](https://pedropark99.github.io/zig-book/) *Free*
**Author:** Pedro Duarte Faria · **Published:** 2024 · **Available as:** Free online / PDF / Print ([Amazon](https://www.amazon.com/Introduction-project-based-Pedro-Duarte-Faria/dp/B0DJZ8G2LH), Leanpub)

An open-source, technical, and introductory book for Zig, designed for both beginners and experienced developers. It explores Zig through small, self-contained projects — a Base64 encoder/decoder, an HTTP server, and an image filter — in the spirit of *Python Crash Course*. Covers language syntax, data structures, memory allocators, filesystem and I/O, optionals, error handling, the build system, C interoperability, parallelism with threads and SIMD, and how Zig compares to C, C++, and Rust.

> 🌟 One of the most complete and widely recommended free Zig resources available.

---

### [Learning Zig](https://www.openmymind.net/learning_zig/) *Free*
**Author:** Karl Seguin · **Available as:** Free online

A concise, highly regarded introduction to Zig aimed at developers coming from garbage-collected languages such as Go, JavaScript, and Python. Cuts straight to the concepts that trip up newcomers: pointers, memory allocation, optionals, and error handling — all without assuming prior systems programming experience.

> 🌟 Frequently cited as the best starting point for developers new to low-level programming.

---

### [Zig Programming Language (ziglearn.org)](https://ziglearn.org) *Free*
**Available as:** Free online

A structured introductory book covering Zig from the basics to more advanced topics. Organized to be read chapter by chapter, with runnable code examples throughout. Kept updated to follow recent Zig releases.

---

### [Zig by Example](https://github.com/boringcollege/zig-by-example) *Free*
**Author:** boringcollege · **Available as:** Free on GitHub

A hands-on introduction to Zig via annotated examples, inspired by *Go by Example*. Covers 40 topics in sequence — from Hello World through values, types, arrays, slices, structs, enums, unions, functions, control flow, optionals, pointers, comptime, generics, memory allocation, ArrayList, HashMap, testing, file I/O, JSON, sorting, the build system, and C interop. Targets **Zig 0.14**. Each topic is a self-contained markdown file with minimal explanation and maximum code clarity.

---

### [Zig by Example (zigbyexample.com)](https://zigbyexample.com) *Free*
**Available as:** Free online

A companion web resource offering short, focused examples demonstrating common Zig patterns — readable in any order, useful as a quick reference while building real projects.

---

### [Zen of Zig](https://zenofzig.com)
**Available as:** Online / eBook

A book series teaching Zig from the ground up, volume by volume. The first volume includes in-browser playgrounds so you can experiment with every chapter without any local setup. Accompanied by original illustrations, and all books are kept up to date with the latest stable Zig release.

---

### [Learning Zig: A Reimagined Introduction to Low-Level Programming with Zig](https://www.amazon.com/Learning-Zig-reimagined-introduction-programming/dp/1835085121)
**Author:** Alex Rios · **Publisher:** Packt · **Published:** November 2025 · **Pages:** 502 · **Available as:** eBook, Print

Written by a software engineer with 17+ years of experience in high-throughput systems across fintech, telecom, and gaming. Takes a "WYWIWIG" (what you write is what you get) philosophy: no hidden control flow, no hidden allocations, no surprises. Each chapter explains the *why* behind Zig's design decisions. Covers C interop, cross-compilation, and packaging for multiple platforms. Suitable for C/C++ developers tired of memory bugs, and for Go/Python developers ready to go closer to the metal.

---

### [Zig Programming: The Complete Beginner's Guide to Zig Language](https://www.amazon.com/Zig-Programming-Complete-Beginners-Language/dp/B0F848JS1L)
**Author:** Julian Lornfeld · **Available as:** Print, Kindle

A comprehensive beginner-focused guide covering Zig's compile-time programming model, type system, and safe manual memory management. Topics include custom data structures, generics with comptime, concurrency and async, C library interop, cross-platform binaries, SIMD, low-level optimizations, and WebAssembly. Discusses how Zig compares to C, Rust, and other systems languages.

---

### [Zig Programming for Developers: A Hands-on Guide](https://www.amazon.com/Zig-Programming-Developers-Hands-High-Performance/dp/B0DKGCXVPJ)
**Author:** Charles Sprinter · **Series:** Zig from Scratch · **Available as:** Print, Kindle

A practical guide covering Zig from syntax and semantics through concurrency, memory safety, and metaprogramming. Packed with real-world examples and exercises. Part of the *Zig from Scratch: Building High-Performance Systems with Zig* series.

---

### [Zig Programming Made Easy: A Comprehensive Guide](https://www.goodreads.com/book/show/220788911)
**Series:** Zig from Scratch · **Available as:** Print, Kindle

A beginner-friendly companion in the Zig from Scratch series, designed for readers who want a gentler on-ramp before tackling advanced topics like comptime and bare-metal programming.

---

### [Mastering Zig: A Clear and Practical Guide to Systems Programming](https://www.amazon.com/dp/9798264712982)
**Available as:** Print

A structured approach to Zig emphasizing real-world applications, practical examples, and best practices that minimize errors and maximize efficiency. Covers memory management, low-level programming, modern safety features, and performance optimization, building skills progressively chapter by chapter. Part of the *Zig Programming* series (Book 1).

---

### [Zig Programming: The Future of High-Performance System Programming](https://www.amazon.com/Zig-Programming-High-Performance-Mastering-Efficient/dp/B0DKP8RW5L)
**Series:** Mastering Zig: Building Robust and Efficient Software · **Available as:** Print, Kindle

Explores Zig's syntax, semantics, and powerful features from an architecture perspective. Covers the type system, memory management, concurrency primitives, and performance optimization, with an eye on shaping the future of systems software.

---

## Advanced Books

### [Zig Programming: A Systems Developer's Guide](https://www.amazon.com/Zig-Programming-Developers-Memory-Safe-High-Performance/dp/B0GKPQ62QJ)
**Author:** Alex M. Harrington · **Available as:** Print, eBook

Written for experienced programmers. Provides an in-depth exploration of Zig fundamentals, advanced syntax, and core design principles — type system, error sets and error unions, explicit memory allocation with allocators, pointers and ownership semantics, and compile-time programming via comptime. Covers concurrency, threading models, synchronization primitives, memory ordering, the build system, and cross-compilation capabilities.

---

### [Effective Zig Programming: Modern Systems Programming with Superior Control](https://www.amazon.com/Effective-Zig-Programming-Systems-Superior/dp/B0F9W85GVD)
**Author:** Jonathan Dupleich · **Available as:** Print, Kindle

From "Hello, Zig!" to advanced concepts like comptime metaprogramming and asynchronous operations. Focuses on how Zig's commitment to explicitness transforms error handling, how manual memory management is paired with innovative safety mechanisms, and how the integrated build system simplifies cross-compilation and complex project management.

---

### [Professional Zig Programming: How to Develop Complex, High-Performance, and Secure Systems](https://www.amazon.com/dp/B0FT92CFMJ)
**Author:** Miguel Farmer · **Series:** Mastering Emerging Programming Languages · **Available as:** Print, Kindle

Aimed at developers ready to build production-grade, secure systems in Zig. Covers advanced API design, security considerations, and the patterns used in large, complex Zig codebases.

---

### [Master Zig Programming: The Fast Track to Blazing Fast System Development](https://www.amazon.com/Master-Zig-Programming-Development-Mastering/dp/B0D9CMS6WT)
**Series:** Zig Programming with Intents: Mastering Modern Systems Programming · **Available as:** Print, Kindle

A fast-paced guide through Zig fundamentals, low-level memory management, concurrency features, and metaprogramming. Aimed at experienced programmers looking to boost development speed and system performance. Companion to *Performance Optimization with Zig Programming* in the same series.

---

### [Zig Essentials: A Concise Guide to Zig's Syntax, Tools, and Ecosystem](https://www.goodreads.com/book/show/229090795-zig-essentials)
**Available as:** Print, eBook

A compact reference covering Zig's syntax, standard library, toolchain, and ecosystem. Useful both as a first read and as a desk reference for developers already writing Zig day-to-day.

---

### [Zig Excellence: Hands-On Projects for Advanced Systems Programming](https://www.amazon.com)
**Available as:** Print, Kindle

Teaches advanced Zig through a series of complete, practical projects. Focuses on building high-performance applications using idiomatic Zig patterns, with an emphasis on the real tradeoffs that arise in production systems.

---

### [Mastering Zig Systems Programming](https://www.goodreads.com/book/show/237098780)
**Series:** Building with Zig: From Systems to Game Engines · **Available as:** Print, Kindle

A comprehensive guide to building high-performance, memory-safe applications with Zig. Spans from systems programming fundamentals through to building game engine components, showing how Zig's design shines across very different domains.

---

### [The Complete Zig Programming Guide](https://www.amazon.com)
**Author:** Matthew D. Passmore · **Available as:** Print, Kindle

Covers systems programming, compile-time power, and low-level development end-to-end. Positioned as a single-volume reference for developers who want a thorough grounding before going into specialized topics.

---

### [Writing An Interpreter In Zig](https://www.definitepotato.dev/books/writing-an-interpreter-in-zig/)

**Available as:** Free online

Borrowing Thorsten Ball's Monkey langauge, learn how to write a fully working Monkey language interpreter in zig, including a lexer, parser, evaluator and REPL. Each chapter builds on each stage of the pipeline and is all self-contained and testable.

---

## Systems, Networking & Embedded

### [Zig System Programming](https://www.amazon.com/dp/B0DQFR11N2)
**Author:** Ronald C. Sheffield · **Series:** Zig Mastery Series (Book 1) · **Available as:** Print, Kindle

A guide to Zig programming fundamentals for developing systems-level software. Starting point of the Zig Mastery Series, covering the building blocks needed before tackling networking and bare-metal programming.

---

### [Networking with Zig Programming Language](https://www.amazon.com/Networking-Programming-Language-High-Performance-Systems-Level/dp/B0DKJQF728)
**Author:** Ronald C. Sheffield · **Series:** Zig Mastery Series (Book 2) · **Available as:** Print, Kindle

A developer's guide to building high-performance, scalable network applications and embedded systems with Zig. Covers TCP/IP, UDP, HTTP, asynchronous programming, zero-copy I/O, and the networking capabilities built into Zig's standard library.

---

### [Bare-Metal Programming with Zig](https://www.amazon.com)
**Author:** Ronald C. Sheffield · **Series:** Zig Mastery Series (Book 3) · **Available as:** Print, Kindle

A hands-on guide to direct hardware control with Zig. Covers bare-metal concepts from first principles, hardware interaction, memory management, interrupt handling, and writing device drivers using Zig's low-level capabilities.

---

### [Zig Network Programming: Practical TCP/UDP, Asynchronous I/O, and High-Performance Networking](https://www.amazon.com)
**Available as:** Print, Kindle

A focused, practical book on networking in Zig. Goes deep on TCP/UDP sockets, async I/O patterns, and high-throughput design, with working code examples throughout.

---

## Free & Online Resources

| Resource | Description |
|---|---|
| [Zig Official Documentation](https://ziglang.org/documentation/master/) | The authoritative language reference |
| [Zig Standard Library Docs](https://ziglang.org/documentation/master/std/) | Full standard library API reference |
| [zig-by-example (boringcollege)](https://github.com/boringcollege/zig-by-example) | 40 annotated examples from Hello World to C interop — targets Zig 0.14 |
| [Zig by Example (zigbyexample.com)](https://zigbyexample.com) | Short, focused examples demonstrating common patterns |
| [zig-cookbook](https://cookbook.ziglang.cc/) | Idiomatic solutions to common programming tasks |
| [Ziglings](https://codeberg.org/ziglings/exercises) | Learn Zig by fixing tiny broken programs — inspired by Rustlings |
| [Zig Playground](https://play.ziglang.org) | Run Zig in the browser — no local setup required |
| [Zig News](https://zig.news) | Community blog with articles and announcements |
| [Zig Monthly](https://zigmonthly.org) | Monthly newsletter covering Zig projects and updates |
| [Zig Weekly](https://zigweekly.com) | Weekly roundup of Zig news, libraries, and discussions |

---

## Interactive & Video

| Resource | Description |
|---|---|
| [Zig ShowTime](https://www.youtube.com/@ZigSHOWTIME) | Community talks and tutorials from across the Zig ecosystem |
| [Introduction to Zig (YouTube playlist)](https://www.youtube.com/watch?v=YXrb-DqsBNU&list=PLV9VPfCMjvoAkgrPTuGCoRnelFwlKXyTS) | Video introduction to Zig and its features |
| [The Zen of Zig — Andrew Kelley](https://www.youtube.com/watch?v=Gv2I7qTux7g) | Foundational talk on the philosophy behind Zig, by its creator |
| [Intro to the Zig Programming Language — GOTO 2022](https://www.youtube.com/watch?v=YXrb-DqsBNU) | Andrew Kelley's accessible overview for a general developer audience |
| [Rust & Zig Combined — GOTO 2023](https://www.youtube.com/watch?v=jIZpKpLCOiU) | Richard Feldman on using Zig and Rust together |

---

## Community & Links

- 🏠 [ziglang.org](https://ziglang.org) — Official Zig website
- 📦 [Codeberg Repository](https://codeberg.org/ziglang/zig) — Official Zig repo (moved from GitHub in November 2025)
- 💬 [Ziggit Community Forum](https://ziggit.dev) — Discussions on language design and development
- 🐦 [Zig Discord](https://discord.gg/gxsFFjE) — Real-time community chat
- 📰 [Andrew Kelley's Blog](https://andrewkelley.me) — Posts from Zig's creator
- 📰 [Loris Cro's Blog](https://kristoff.it) — Writing from Zig's VP of Community
- ⭐ [awesome-zig](https://github.com/C-BJ/awesome-zig) — Curated list of Zig libraries, tools, and projects
- 📖 [zig-learning (zouyee)](https://github.com/zouyee/zig-learning) — Links to blog posts, articles, videos, and more

---

## Contributing

Your contributions are always welcome! Please follow these guidelines:

- Each book entry should include: title (with link), author, publisher (if applicable), format (Free / eBook / Print), and a short description.
- Books must be specifically about Zig or contain substantial Zig content.
- For free online resources, describe clearly what makes them valuable and distinct.
- No duplicate entries. If a book already appears, open an issue to suggest description improvements.
- Keep descriptions factual and concise — this is a reference list, not a marketing page.

---

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright and related or neighboring rights to this work.
