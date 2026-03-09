# Security Policy

## Supported Versions

| Version | Supported          |
|---------|--------------------|
| 1.0.x   | ✅ Yes             |
| < 1.0   | ❌ No              |

## Reporting a Vulnerability

The Urus Foundation takes security seriously. If you discover a security vulnerability in any of our projects, please report it responsibly.

### How to Report

**DO NOT** create a public GitHub issue for security vulnerabilities.

Instead, please email us at: **[urusfoundation@gmail.com](mailto:urusfoundation@gmail.com)**

Include the following information:

- **Description** of the vulnerability
- **Steps to reproduce** the issue
- **Impact assessment** — what could an attacker achieve?
- **Affected version(s)**
- **Suggested fix** (if you have one)

### What to Expect

- **Acknowledgment** within 48 hours of your report
- **Status update** within 7 days with our assessment
- **Resolution timeline** communicated based on severity
- **Credit** in the security advisory (if desired)

### Severity Levels

| Severity | Description | Target Resolution |
|----------|-------------|-------------------|
| **Critical** | Remote code execution, compiler producing unsafe binaries | 24-48 hours |
| **High** | Memory safety bypass, type system unsoundness | 1 week |
| **Medium** | Denial of service, information disclosure | 2 weeks |
| **Low** | Minor issues with limited impact | Next release |

## Security Best Practices

When using Urus in production:

- Always use the latest stable version
- Review generated C code (`--emit-c`) for sensitive applications
- Report any unexpected compiler behavior immediately
- Keep your GCC toolchain up to date

## Acknowledgments

We thank the security researchers who help keep Urus safe. Contributors who report valid vulnerabilities will be acknowledged here (with permission).

---

*This policy is subject to change. Last updated: March 2026.*
