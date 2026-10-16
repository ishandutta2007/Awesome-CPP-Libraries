# ⚡ Awesome C++ Libraries & Frameworks

<p align="center">
  <img src="assets/banner.svg" alt="Awesome C++ Libraries Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <img src="https://img.shields.io/badge/Language-C%2B%2B17%20%7C%20C%2B%2B20%20%7C%20C%2B%2B23-blue.svg?style=flat-square" alt="Language" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License" />
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome" />
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🚀 Overview & Ecosystem Scope

Welcome to the ultimate curated directory of **C++ Libraries, Frameworks, and Developer Platforms**. Modern C++ (C++17, C++20, and C++23) powers high-throughput distributed systems, game development engines, embedded devices, trading infrastructure, machine learning runtimes, and real-time graphics pipelines.

This repository tracks notable **commercial SaaS platforms, developer runtime tooling, and top-tier open-source GitHub projects**. Whether building ultra-low-latency financial networking systems or cross-platform desktop applications, these libraries provide production-tested primitives without having to reinvent core infrastructure.

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [💼 SaaS & Commercial Hosted Platforms](#-saas--commercial-hosted-platforms)
- [⭐ Open-Source GitHub Projects](#-open-source-github-projects)
  - [Top Starred Ecosystem Leaders](#-top-starred-ecosystem-leaders)
  - [Specialized Frameworks & Portability Layers](#-specialized-frameworks--portability-layers)
- [📈 Star History](#-star-history)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support](#-support)
- [⚠️ Disclaimer](#-disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global C and C++ software development tools and IDE ecosystem is estimated at **$5.1 billion** (projected to exceed **$10.8 billion** by 2032 with a CAGR of ~8.5%), situated within the broader **$8+ billion** software engineering developer tools market. 

The sector exhibits **moderate fragmentation** with a bifurcated dynamic:
- **Core Toolchain & IDE Tier (Highly Concentrated)**: Heavily consolidated around dominant players—notably Microsoft (MSVC / Visual Studio), The Qt Company, and LLVM/GCC ecosystems—where massive network effects, IDE integration, and enterprise LTS contracts dominate commercial spend.
- **Library & Middleware Tier (Moderately Fragmented)**: Highly diverse and open-source driven. Rather than a winner-take-all outcome, specialized domain niches (e.g., OpenCV for computer vision, nlohmann/json for serialization, gRPC/Protobuf for RPC, JUCE for audio, and Abseil/Boost for general primitives) thrive side-by-side with no single framework monopolizing modern C++ application stacks.

---

## 💼 SaaS & Commercial Hosted Platforms

| Platform | Provider / Company | Valuation / Revenue | Starting Pricing | Free Tier Limits | Description |
| --- | --- | --- | --- | --- | --- |
| **Microsoft Visual C++ / Visual Studio** | Microsoft Corporation | ~$3.1T valuation / $245B+ annual revenue | $45/user/month (Monthly Subscription) or $499 (Perpetual Standalone) | Free forever via Visual Studio Community: Limited to individual developers, open-source projects, classroom learning, and organizations with ≤$1M annual gross revenue & ≤250 PCs (up to 5 users). | Commercial IDE, runtime distribution, and MSVC toolchain support for modern C++ development with Azure integration. |
| **Embarcadero C++Builder** | Idera, Inc. | ~$3B valuation / ~$250M+ annual revenue | $1,500/developer (Professional perpetual license with 1-yr update subscription) | Free forever via Community Edition: Limited to individual developers and teams of ≤5 developers with annual company revenue under $5,000 USD. Also offers a 30-day fully functional free evaluation trial. | Modern C++ IDE and component framework (VCL & FireMonkey) for cross-platform Windows and iOS/desktop development. |
| **Qt Commercial** | The Qt Company (Qt Group Plc) | ~$1B market cap (€900M+) / €216.3M annual revenue | $495/developer/month ($5,940/year billed annually) for Qt for Application Development (Professional) | 10-day free trial of commercial edition (evaluation only, no commercial/production rights). Alternatively, Qt Community is free forever under open-source (LGPLv3/GPLv3) licensing requiring relinking/source sharing. | Commercial licensing, validated cross-platform runtime builds, LTS releases, and enterprise support/indemnification for Qt. |

---

## ⭐ Open-Source GitHub Projects

All open-source repositories below are sorted in **descending order by GitHub star count**. Star count badges display current community traction and link directly to each repository's stargazers.

### 🌟 Top Starred Ecosystem Leaders

- **[OpenCV](https://github.com/opencv/opencv)** [![GitHub stars](https://img.shields.io/github/stars/opencv/opencv?style=social&color=white)](https://github.com/opencv/opencv/stargazers)  
  *Open Source Computer Vision Library* (Apache-2.0).  
  The de facto industry standard library for real-time computer vision, image processing, machine learning, and deep neural network acceleration across desktop, mobile, and embedded hardware.

- **[Protocol Buffers](https://github.com/protocolbuffers/protobuf)** [![GitHub stars](https://img.shields.io/github/stars/protocolbuffers/protobuf?style=social&color=white)](https://github.com/protocolbuffers/protobuf/stargazers)  
  *Google's data interchange format and serialization engine* (BSD-3-Clause).  
  Language-neutral, platform-neutral, extensible mechanism for serializing structured data. Extremely fast, lightweight, and used across hyperscale microservices.

- **[JSON for Modern C++](https://github.com/nlohmann/json)** [![GitHub stars](https://img.shields.io/github/stars/nlohmann/json?style=social&color=white)](https://github.com/nlohmann/json/stargazers)  
  *Intuitive, single-header JSON library for modern C++* (MIT).  
  First-class JSON integration designed to feel like native STL syntax with full type safety, serialization, deserialization, and zero third-party dependencies.

- **[gRPC](https://github.com/grpc/grpc)** [![GitHub stars](https://img.shields.io/github/stars/grpc/grpc?style=social&color=white)](https://github.com/grpc/grpc/stargazers)  
  *High-performance, open-source universal RPC framework* (Apache-2.0).  
  Connects, distributes, and orchestrates polyglot microservices with bidirectional streaming, pluggable authentication, tracing, and HTTP/2 transport.

- **[GoogleTest](https://github.com/google/googletest)** [![GitHub stars](https://img.shields.io/github/stars/google/googletest?style=social&color=white)](https://github.com/google/googletest/stargazers)  
  *Google Testing and Mocking Framework* (BSD-3-Clause).  
  The gold standard for C++ unit testing, test suites, parameterization, XML test report generation, and GoogleMock object stubbing.

- **[Folly](https://github.com/facebook/folly)** [![GitHub stars](https://img.shields.io/github/stars/facebook/folly?style=social&color=white)](https://github.com/facebook/folly/stargazers)  
  *Facebook's open-source library of C++14/17 performance components* (Apache-2.0).  
  Features hyperscale performance primitives: `folly::FBString`, `ConcurrentHashMap`, `PackedSyncPtr`, asynchronous `Future`/`Executor`, `IOBuf` zero-copy buffers, and high-efficiency memory arenas.

- **[spdlog](https://github.com/gabime/spdlog)** [![GitHub stars](https://img.shields.io/github/stars/gabime/spdlog?style=social&color=white)](https://github.com/gabime/spdlog/stargazers)  
  *Super fast C++ logging library* (MIT).  
  Header-only / compiled lightning-speed asynchronous and synchronous logging with rich formatting, multi-threading safety, and rotating file sinks.

- **[libuv](https://github.com/libuv/libuv)** [![GitHub stars](https://img.shields.io/github/stars/libuv/libuv?style=social&color=white)](https://github.com/libuv/libuv/stargazers)  
  *Multi-platform asynchronous event-driven I/O library* (MIT).  
  Powers Node.js and distributed runtimes; offers epoll/kqueue/IOCP event loops, non-blocking TCP/UDP sockets, DNS resolution, and thread-pool execution.

- **[{fmt}](https://github.com/fmtlib/fmt)** [![GitHub stars](https://img.shields.io/github/stars/fmtlib/fmt?style=social&color=white)](https://github.com/fmtlib/fmt/stargazers)  
  *Fast, safe, and extensible formatting library* (MIT).  
  The foundational library behind C++20's `std::format`; provides a type-safe, compile-time checked alternative to `printf` and `iostream`.

- **[Catch2](https://github.com/catchorg/Catch2)** [![GitHub stars](https://img.shields.io/github/stars/catchorg/Catch2?style=social&color=white)](https://github.com/catchorg/Catch2/stargazers)  
  *Modern, C++-native test framework for unit-tests, TDD and BDD* (BSL-1.0).  
  Renowned for natural expression assertion syntax, BDD test sections, fast compilation, and seamless CLI test runners.

- **[Abseil](https://github.com/abseil/abseil-cpp)** [![GitHub stars](https://img.shields.io/github/stars/abseil/abseil-cpp?style=social&color=white)](https://github.com/abseil/abseil-cpp/stargazers)  
  *Google's collection of standard library augmentation modules* (Apache-2.0).  
  Extracted from Google's internal monorepo; ships ultra-optimized Swiss Tables (`flat_hash_map`), `absl::StatusOr<T>`, synchronization locks, flags, strings, and 128-bit integers.

- **[RapidJSON](https://github.com/Tencent/rapidjson)** [![GitHub stars](https://img.shields.io/github/stars/Tencent/rapidjson?style=social&color=white)](https://github.com/Tencent/rapidjson/stargazers)  
  *A fast JSON parser/generator for C++ with SAX/DOM styles* (MIT).  
  Tencent's high-speed parser with SIMD acceleration (SSE2/SSE4.2/NEON), memory pools, and full JSON Schema validation.

- **[ZeroMQ (libzmq)](https://github.com/zeromq/libzmq)** [![GitHub stars](https://img.shields.io/github/stars/zeromq/libzmq?style=social&color=white)](https://github.com/zeromq/libzmq/stargazers)  
  *Universal messaging library with sockets that act like concurrency primitives* (MPL-2.0).  
  Carries messages across inproc, IPC, TCP, TIPC, and multicast; perfect for pub-sub, push-pull, and request-reply pipelines.

- **[POCO C++ Libraries](https://github.com/pocoproject/poco)** [![GitHub stars](https://img.shields.io/github/stars/pocoproject/poco?style=social&color=white)](https://github.com/pocoproject/poco/stargazers)  
  *Cross-platform C++ libraries for network- and internet-based applications* (BSL-1.0).  
  Comprehensive network-centric foundation: HTTP/REST servers, WebSocket, SSL/TLS, database abstraction, thread pools, XML/JSON parsing, and configuration management.

- **[EASTL](https://github.com/electronicarts/EASTL)** [![GitHub stars](https://img.shields.io/github/stars/electronicarts/EASTL?style=social&color=white)](https://github.com/electronicarts/EASTL/stargazers)  
  *Electronic Arts Standard Template Library* (BSD-3-Clause).  
  Engineered specifically for game development and memory-constrained real-time environments with fine-grained custom allocator control and predictable cache friendliness.

- **[JUCE](https://github.com/juce-framework/JUCE)** [![GitHub stars](https://img.shields.io/github/stars/juce-framework/JUCE?style=social&color=white)](https://github.com/juce-framework/JUCE/stargazers)  
  *Cross-platform audio application framework and DSP plug-in suite* (GPLv3 / Commercial).  
  The industry benchmark for building VST, AU, AAX audio plug-ins, digital audio workstations (DAWs), and real-time interactive synthesizers.

- **[Boost C++ Libraries](https://github.com/boostorg/boost)** [![GitHub stars](https://img.shields.io/github/stars/boostorg/boost?style=social&color=white)](https://github.com/boostorg/boost/stargazers)  
  *Peer-reviewed portable C++ source libraries* (BSL-1.0).  
  Over 120 individual libraries covering Asio (async I/O), Beast (HTTP/WebSocket), Filesystem, Graph, Spirit parsing, Multi-Index, and lock-free concurrency. The historical foundation for modern ISO C++ standards.

- **[wxWidgets](https://github.com/wxWidgets/wxWidgets)** [![GitHub stars](https://img.shields.io/github/stars/wxWidgets/wxWidgets?style=social&color=white)](https://github.com/wxWidgets/wxWidgets/stargazers)  
  *Cross-platform GUI library with native platform appearance* (wxWindows Library Licence).  
  Wraps native OS controls on Windows, macOS, and Linux/GTK for genuine native look-and-feel, dockable window systems, and 2D drawing.

- **[CLI11](https://github.com/CLIUtils/CLI11)** [![GitHub stars](https://img.shields.io/github/stars/CLIUtils/CLI11?style=social&color=white)](https://github.com/CLIUtils/CLI11/stargazers)  
  *Command line parser for C++11 and beyond* (BSD-3-Clause).  
  Friendly, single-header or modular command-line parser with type safety, subcommands, option groups, and configuration file parsing.

- **[Qt Base (Core / GUI)](https://github.com/qt/qtbase)** [![GitHub stars](https://img.shields.io/github/stars/qt/qtbase?style=social&color=white)](https://github.com/qt/qtbase/stargazers)  
  *Base components of the Qt cross-platform framework* (LGPLv3 / GPLv3 / Commercial).  
  Provides object properties, signals & slots, guarded pointers, thread pools, event loops, and internationalization primitives.

- **[gflags](https://github.com/gflags/gflags)** [![GitHub stars](https://img.shields.io/github/stars/gflags/gflags?style=social&color=white)](https://github.com/gflags/gflags/stargazers)  
  *C++ library that implements commandline flags processing* (BSD-3-Clause).  
  Google's battle-tested command-line argument configuration tool used across distributed clusters.

- **[BDE (Bloomberg Development Environment)](https://github.com/bloomberg/bde)** [![GitHub stars](https://img.shields.io/github/stars/bloomberg/bde?style=social&color=white)](https://github.com/bloomberg/bde/stargazers)  
  *Bloomberg's enterprise-grade core C++ foundation* (Apache-2.0).  
  Powers mission-critical financial trading applications with multi-tier memory allocation models, scalable containers, and deterministic thread facilities.

- **[Apache Portable Runtime (APR)](https://github.com/apache/apr)** [![GitHub stars](https://img.shields.io/github/stars/apache/apr?style=social&color=white)](https://github.com/apache/apr/stargazers)  
  *Portability layer and runtime utilities for high-reliability software* (Apache-2.0).  
  Provides underlying OS abstractions for network sockets, process control, file operations, thread synchronization, and shared memory used in the Apache Web Server.

- **[eckit (ECMWF)](https://github.com/ecmwf/eckit)** [![GitHub stars](https://img.shields.io/github/stars/ecmwf/eckit?style=social&color=white)](https://github.com/ecmwf/eckit/stargazers)  
  *C++ toolkit for climate and numerical weather prediction applications* (Apache-2.0).  
  Offers space-partitioning trees, high-speed serialization, memory-mapped files, and MPI wrappers for high-performance computing clusters.

---

### 🛠️ Specialized Frameworks & Portability Layers

- **[Asio (Standalone)](https://github.com/chriskohlhoff/asio)** [![GitHub stars](https://img.shields.io/github/stars/chriskohlhoff/asio?style=social&color=white)](https://github.com/chriskohlhoff/asio/stargazers) — Standalone cross-platform C++ library for network and low-level I/O programming.
- **[Eigen](https://gitlab.com/libeigen/eigen)** — High-level C++ template library for linear algebra, matrices, vectors, numerical solvers, and related algorithms.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-CPP-Libraries&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-CPP-Libraries&type=date&legend=top-left)

---

## 🤝 How to Contribute

Contributions are warmly encouraged! To keep this repository top-quality and reliable:

1. 🍴 **Fork** the repository.
2. 🌿 Create a descriptive feature branch (`git checkout -b feature/add-new-library`).
3. 📝 Update `README.md` following the established sorting order, including star badge links (`https://img.shields.io/github/stars/{owner}/{repo}?style=social&color=white`) linking to `/stargazers`.
4. ✅ Commit with clear messaging and open a Pull Request.

---

## 💖 Support

Thank you for exploring and utilizing the **Awesome C++ Libraries** ecosystem! 🚀

If you found this resource helpful for your projects, architecture planning, or C++ development workflow, please consider:
- ⭐ **Starring** the repository on GitHub
- 🍴 **Forking** and contributing library updates
- 📢 **Sharing** with your fellow developers, engineers, and teams
- ☕ **Buying a coffee & sponsoring ongoing development**: Support this project and other developer tools via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a community-curated collection intended for educational and architectural research purposes.
- Always inspect library licenses (**MIT, Apache-2.0, BSL-1.0, LGPL, GPL, or Commercial**) to confirm compatibility with your organization's deployment and distribution model.
- Performance profiles and architectural trade-offs differ significantly between frameworks; benchmark within your target runtime environment prior to production commitment.

---

<p align="center">
  <b>Built with ❤️ for C++ Developers, Systems Engineers &amp; High-Performance Architects worldwide.</b>
</p>
