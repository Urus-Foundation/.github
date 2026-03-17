<div align="center">

<img src="https://raw.githubusercontent.com/Urus-Foundation/initial-resource/main/assets/banner_urus.png" width="600">

**Building the future of systems programming — safe, simple, and portable.**

[![Website](https://img.shields.io/badge/Website-urusfoundation.org-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://github.com/Urus-Foundation)
[![Email](https://img.shields.io/badge/Email-urusfoundation%40gmail.com-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:urusfoundation@gmail.com)
[![License](https://img.shields.io/badge/License-Apache_2.0-green?style=for-the-badge)](https://github.com/Urus-Foundation/Urus/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/Urus-Foundation/Urus?style=for-the-badge&logo=github&color=gold)](https://github.com/Urus-Foundation/Urus)

---

</div>

## 🐂 About Us

**Urus Foundation** is an open-source organization dedicated to developing **Urus** — a modern, statically-typed programming language that combines **Rust-like safety** with **Python-like simplicity**, transpiling to portable **C11**.

We believe systems programming shouldn't require choosing between safety and simplicity. Urus bridges that gap with a clean, modern design that compiles to native binaries through standard C11 — running anywhere GCC runs.

## 🚀 Flagship Project

### [Urus Programming Language](https://github.com/Urus-Foundation/Urus)

> *Rust-like safety with Python-like simplicity, transpiling to C11.*

| | |
|---|---|
| **Safer than C** | Reference counting, bounds checking, immutable by default |
| **Simpler than Rust** | No borrow checker, no lifetimes |
| **Faster than Python** | Compiles to native binary via C11 |
| **More portable than Go** | Standard C11 — runs anywhere GCC runs |

```rust
fn fibonacci(n: int) -> int {
    if n <= 1 {
        return n
    }
    return fibonacci(n - 1) + fibonacci(n - 2)
}

fn main() {
    let result = fibonacci(10)
    println(f"Fibonacci(10) = {result}")
}
```

#### Compiler Pipeline
```
Source (.urus) → Lexer → Parser (AST) → Sema (Type Check) → Codegen (C11) → GCC → Native Binary
```

## 🗺️ Roadmap

| Version | Highlights |
|---------|-----------|
| **v0.3/1** | Default parameters, enhanced error messages, warning system |
| **v0.4/1** | Type aliases, Optional type, type inference |
| **v0.5/1** | Methods (`impl` blocks), traits/interfaces, generics, closures, stdlib, package manager |
| **v2.0/1** | Async/await, concurrency, WASM target, self-hosting compiler, LSP server |

## 📦 Our Repositories

| Repository | Description | Status |
|-----------|-------------|--------|
| [**Urus**](https://github.com/Urus-Foundation/Urus) | The Urus compiler and runtime | ✅ Stable v0.2/2 (fixed) |
| [**urus-treesitter**](https://github.com/Urus-Foundation/urus-treesitter) | Tree-sitter grammar for Urus (syntax highlighting & editor support) | 🔨 In Development |
| [**editor-support**](https://github.com/Urus-Foundation/editor-support) | Editor extensions and plugins for the Urus Programming Language | ✅ Stable Vscode (v0.3.0), Acode (v0.3.0) |

## 🤝 Contributing

We welcome contributions from developers of all experience levels! Here's how you can get involved:

- **🐛 Report Bugs** — Found an issue? [Open a bug report](https://github.com/Urus-Foundation/Urus/issues/new?template=bug_report.yml)
- **💡 Suggest Features** — Have an idea? [Submit a feature request](https://github.com/Urus-Foundation/Urus/issues/new?template=feature_request.yml)
- **📝 Improve Docs** — Help us make documentation clearer and more comprehensive
- **🔧 Submit Code** — Check out our [Contributing Guide](https://github.com/Urus-Foundation/Urus/blob/main/CONTRIBUTING.md) to get started

## 🏗️ Tech Stack

<div align="center">

![C](https://img.shields.io/badge/C11-00599C?style=for-the-badge&logo=c&logoColor=white)
![GCC](https://img.shields.io/badge/GCC-A42E2B?style=for-the-badge&logo=gnu&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)

</div>

## 🌟 Inspired By

Urus takes inspiration from the best ideas in modern language design:

- **Rust** — Enums, pattern matching, `Result` type, immutability-first
- **Go** — Simplicity, fast compilation, minimal footprint
- **Zig** — Transpile-to-C philosophy, minimal runtime
- **Python** — F-string interpolation, readable syntax

## 📬 Get in Touch

- **Email:** [urusfoundation@gmail.com](mailto:urusfoundation@gmail.com)
- **GitHub:** [github.com/Urus-Foundation](https://github.com/Urus-Foundation)

---

<div align="center">

**⭐ If you find Urus interesting, give us a star — it helps the project grow!**

*Built with passion by the Urus Foundation team.*

</div>
