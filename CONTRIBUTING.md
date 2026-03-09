# Contributing to Urus Foundation Projects

Thank you for your interest in contributing to the Urus Foundation! This guide applies to all repositories under the organization.

## Getting Started

1. **Fork** the repository you want to contribute to
2. **Clone** your fork locally
3. **Create a branch** for your changes (`git checkout -b feature/my-feature`)
4. **Make your changes** and commit them with clear messages
5. **Push** to your fork and open a **Pull Request**

## Development Setup

### Prerequisites

- **GCC 8+** (MinGW-w64/MSYS2 on Windows)
- **CMake 3.10+**
- **Git**

### Building the Urus Compiler

```bash
git clone https://github.com/Urus-Foundation/Urus.git
cd Urus
cmake -S . -B build
cmake --build build
```

### Running Tests

```bash
# Linux / macOS
cd tests && bash run_tests.sh

# Windows
cd tests && run_tests.bat
```

## Contribution Guidelines

### Code Style

- Use consistent indentation (4 spaces)
- Follow existing naming conventions in the codebase
- Keep functions focused and reasonably sized
- Add comments for complex logic

### Commit Messages

Write clear, descriptive commit messages:

```
<type>: <short summary>

<optional detailed description>
```

**Types:** `feat`, `fix`, `docs`, `refactor`, `test`, `chore`, `perf`

**Examples:**
- `feat: add default parameter values to functions`
- `fix: correct bounds checking for empty arrays`
- `docs: update installation guide for Windows`

### Pull Requests

- Keep PRs focused on a single change
- Include tests for new features or bug fixes
- Update documentation if your change affects public behavior
- Ensure all tests pass before submitting
- Fill out the PR template completely

## Reporting Issues

- Use the provided issue templates (Bug Report or Feature Request)
- Search existing issues before creating a new one
- Provide minimal reproduction steps for bugs
- For security vulnerabilities, see [SECURITY.md](https://github.com/Urus-Foundation/Urus/blob/main/SECURITY.md)

## Code of Conduct

All contributors are expected to follow our [Code of Conduct](https://github.com/Urus-Foundation/Urus/blob/main/CODE_OF_CONDUCT.md). Please be respectful and constructive in all interactions.

## Questions?

If you have questions about contributing, feel free to:
- Open a [Discussion](https://github.com/Urus-Foundation/Urus/discussions)
- Email us at [urusfoundation@gmail.com](mailto:urusfoundation@gmail.com)

---

Thank you for helping make Urus better! Every contribution matters.
