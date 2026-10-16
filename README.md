# Awesome-CPP-Libraries

## Top C++ Libraries Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on General-Purpose Frameworks, Cross-Platform Development & Performance Primitives*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **C++ Libraries**. These tools provide the foundational building blocks—containers, algorithms, concurrency primitives, networking, and cross-platform abstractions—that C++ developers rely on to build robust, high-performance applications without reinventing core infrastructure.



**Examples** include Boost, Qt Core, POCO C++ Libraries, Abseil, Folly, wxWidgets, JUCE, EASTL, APR, and Modern C++ Toolkit (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, cross-platform development, and performance-critical C++ infrastructure—ideal for systems programmers, application developers, and organizations seeking transparent, vendor-independent C++ tooling.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **Commercial C++ Support & Distribution Platforms** (Qt Commercial, Embarcadero C++Builder, Microsoft Visual C++ Redistributable)  

  Commercial platforms provide **licensed support, validated builds, and distribution guarantees** for C++ libraries. Qt Commercial adds **commercial licensing for Qt** with support and indemnification. These are relevant when **SLAs or proprietary licensing terms** are required.



## Open-Source GitHub Projects



- **[Boost C++ Libraries](https://github.com/boostorg/boost)**  

  **Peer-reviewed portable C++ source libraries** (Boost Software License) . **The most comprehensive and widely adopted C++ library collection**—**120+ individual libraries** covering **algorithms, containers, concurrency, filesystem, networking, parsing, math, and more** . **The standard for C++ libraries that complement the STL**—many Boost libraries have been adopted into the C++ standard (smart pointers, threads, regex, filesystem) . **Features**: **Asio** (networking and async I/O), **Beast** (HTTP/WebSocket), **Filesystem**, **Thread**, **Regex**, **Spirit** (parser combinator), **Multi-index containers**, **Graph**, and **MySQL/Redis/MQTT5 clients** built on Asio . **The reference implementation for general-purpose C++ libraries** .



- **[Qt Core](https://doc.qt.io/qt-6.8/qtcore-index.html)**  

  **Cross-platform application and UI framework** (LGPL-3.0 / Commercial) . **The most widely used C++ GUI framework**—**Qt Core provides the non-GUI foundation** for all Qt applications . **Key features**: **signals and slots** for seamless object communication, **queryable object properties**, **hierarchical object trees with guarded pointers (QPointer)**, **platform-independent threading and concurrent programming**, **resource system for embedding binary files in executables**, **platform-independent I/O and containers** . **The reference implementation for cross-platform C++ development** .



- **[POCO C++ Libraries](https://github.com/pocoproject/poco)**  

  **Cross-platform C++ libraries for building network- and internet-based applications** (Boost Software License) . **The "leaner substitute for Boost"** for network-centric applications . **Key features**: **threading and concurrent programming**, **JSON and YAML parsing**, **object serialization with compression**, **configuration file support**, **filesystem abstraction**, **regular expressions**, **socket networking**, **HTTP protocol**, **async I/O**, **exception handling and stack dumping**, **MPI wrapper**, **linear algebra abstraction (BLAS, MKL, Armadillo, Eigen3)**, **advanced containers**, **space partition trees**, and **file-mapped arrays** . **Latest 1.15.0** ships critical security patches for bundled expat, PCRE2, SQLite, libpng, and LZMA SDK . **The reference implementation for network-centric C++ applications** .



- **[Abseil (Google)](https://github.com/abseil/abseil-cpp)**  

  **An open-source collection of C++ code designed to augment the C++ standard library** (Apache-2.0) . **Google's C++ common libraries extracted from their own codebase**—**extensively tested and used in production** at Google scale . **Key features**: **`absl::Mutex`** (alternative to `std::mutex`), **Swiss table containers** (unordered map/set with better performance), **`absl::Status` and `absl::StatusOr<T>`** (error handling), **flags library**, **strings utilities**, **synchronization primitives**, **time abstractions**, **128-bit integers**, **cleanup callbacks**, and **hash framework** . **The reference implementation for augmenting the C++ standard library** .



- **[Folly (Facebook)](https://github.com/facebook/folly)**  

  **An open-source C++ library developed and used at Facebook** (Apache-2.0) . **Facebook's open-source library**—**a library of C++17 components designed with practicality and efficiency in mind** . **Key features**: **`folly::FBString`** (optimized string), **`folly::PackedSyncPtr`**, **`folly::SmallLocks`**, **`folly::ConcurrentHashMap`**, **`folly::Arena`**, **`folly::Future`**, **`folly::Executor`**, **`folly::IOBuf`** (buffer management), **`folly::json`**, **`folly::Format`**, and **`folly::Singleton`** . **Performance at large scale is the unifying theme**—**Folly complements Boost and std** rather than competing, defining components only when **not available or not meeting the needed performance profile** . **The reference implementation for performance-critical C++ at scale** .



- **[wxWidgets](https://www.wxwidgets.org/)**  

  **Cross-platform GUI library with native look and feel** (wxWindows Licence — L-GPL with exception) . **The only C++ GUI library built by wrapping native GUI widgets**—**applications adopt the look and feel appropriate to each platform** . **Key features**: **single API for Windows, macOS, Linux/Unix**, **over 100 example programs**, **nearly 200,000 lines of documentation**, **flexible event system**, **2D path-based drawing with transparency**, **built-in support for BMP, PNG, JPEG, GIF, XPM, PNM, PCX, TGA**, **printing, help, clipboard, drag-and-drop**, **native HTML rendering integration**, **dockable windows framework**, and **powerful text editing widget with syntax highlighting** . **Used by AOL, AMD, Lockheed Martin, Xerox, NASA, Audacity, FileZilla** . **The reference implementation for native cross-platform GUI applications** .



- **[JUCE](https://github.com/juce-framework/JUCE)**  

  **Open-source cross-platform C++ application framework for audio applications and plug-ins** (ISC / GPL / Commercial) . **The standard for audio application development**—**used for rapidly developing high-quality desktop and mobile applications, including VST, AU (and AUv3), RTAS, and AAX audio plug-ins** . **Key features**: **Projucer** (project generation tool with live-coding engine), **`juce_audio_basics`, `juce_audio_devices`, `juce_audio_processors`** modules, **`AudioAppComponent`** for real-time audio processing, **`AudioPluginHost`** for testing plug-ins, **support for Xcode, Visual Studio, Android Studio, Code::Blocks, CLion, and Linux Makefiles** . **The reference implementation for audio/MIDI applications and plug-ins** .



- **[EASTL (Electronic Arts)](https://github.com/electronicarts/EASTL)**  

  **Electronic Arts Standard Template Library** (Modified BSD License — 3-Clause) . **A C++ template library of containers, algorithms, and iterators useful for runtime and tool development across multiple platforms** . **Emphasis on high performance above all other considerations**—**suitable for tools and shipping applications on multiple platforms from embedded systems to servers and mainframes** . **Created by Paul Pedriana and maintained for roughly 10 years before being open-sourced** . **The reference implementation for high-performance STL replacement in game development** .



- **[Apache Portable Runtime (APR)](https://apr.apache.org/)**  

  **Library of routines that allows programmers to write a program once and be able to compile it anywhere** (Apache-2.0) . **The Apache HTTP Server's portability layer**—**abstracts the OS into a series of Apache-related functions, making it simpler to port Apache to other platforms** . **Key features**: **file reading and writing**, **character set conversion**, **network communications via sockets**, **time management**, **string management**, **UNIX password management**, **table management**, **UUID generation**, **filename canonicalization**, **random data generation**, **global lock management**, **threads and process management**, **dynamic library loading**, **memory-mapped and shared memory** . **APR-util adds hashing, UUID, DBD/DBM client interfaces, LDAP SSL, XML parsing (expat), charset translation (iconv)** . **The reference implementation for OS portability abstraction** .



### Additional Strong Open-Source Options



- **[eckit (ECMWF)](https://github.com/ecmwf/eckit)** — Cross-platform C++ toolkit for building tools and applications at ECMWF (Apache-2.0) . **The leaner Boost substitute for weather/climate applications**—**multi-threading, JSON/YAML parsing, serialization with compression, configuration, filesystem, regex, socket networking, HTTP, async I/O, MPI wrapper, linear algebra (BLAS/MKL/Armadillo/Eigen3), space partition trees, and file-mapped arrays** .

- **[modern-cpp-toolkit](https://github.com/your-repo/modern-cpp-toolkit)** — Modern C++ toolkit (open-source) . **The collection of modern C++ libraries** .

- **[BDE (Bloomberg)](https://github.com/bloomberg/bde)** — Bloomberg Development Environment (Apache-2.0) . **The enterprise-grade C++ foundation library** used across Bloomberg's trading systems .

- **[Folly](https://github.com/facebook/folly)** — See above.

- **[Abseil](https://github.com/abseil/abseil-cpp)** — See above.

- Community **n8n** workflows for C++ library dependency tracking and build alerting.



**Frameworks for building custom systems**: Combine **Boost** for general-purpose utilities with **Qt Core** for cross-platform application development, **POCO** for network-centric services, **Abseil** for standard library augmentation, and **Folly** for high-performance primitives—creating a comprehensive C++ development foundation.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- C++ libraries must be evaluated for **license compatibility** with your project. **Boost uses a permissive license**; **Qt requires LGPL compliance or commercial licensing**; **wxWidgets uses an L-GPL exception allowing static linking without source disclosure**; **JUCE uses a tiered license (ISC for open source, GPL, or commercial)** .

- **The "standard library vs. library ecosystem" distinction matters.** **Abseil and Folly explicitly complement the C++ standard library** rather than replace it. **Boost provides what the standard library lacks** and serves as a **proving ground for standard adoption** (many Boost libraries became std features). **Choose based on what your project actually needs**—don't pull in a framework for a single utility class.

- **Performance characteristics vary dramatically.** **Folly is designed for performance at large scale** with idiosyncratic designs (PackedSyncPtr, SmallLocks) . **EASTL emphasizes high performance for game development** . **POCO is optimized for network applications** . **Boost prioritizes portability and correctness** . **Match the library to your workload.**

- **Cross-platform GUI requires a framework decision.** **Qt provides a complete application framework with signals/slots and a resource system** . **wxWidgets wraps native widgets for true native look and feel** . **JUCE is the standard for audio applications and plug-ins** . **The choice depends on whether you prioritize native appearance, audio/MIDI capabilities, or application framework completeness.**

- **Security patches require active maintenance.** **POCO 1.15.0 shipped critical security fixes for bundled expat, PCRE2, SQLite, libpng, and LZMA SDK** . **Track security advisories for your dependencies**—bundled third-party libraries are a common vulnerability vector .

- Self-hosted open-source solutions require proper build system integration (CMake, Bazel), dependency management, and ongoing maintenance. **C++ dependency management remains fragmented**—vcpkg, Conan, and system package managers all have trade-offs.



---



**Made for C++ developers, systems programmers, and organizations building transparent library infrastructure.**  

Let's make C++ Libraries more open, data-driven, and performant.
