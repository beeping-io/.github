# 🛡️ Security Policy

## 📌 Reporting a vulnerability

The Beeping team takes security seriously. **Thank you for taking the time to responsibly disclose any issues you find.**

### How to report

If you discover a security vulnerability in any component of the Beeping Platform, **do not open a public GitHub issue**.

Instead, please use one of these private channels:

1. 🔒 **Preferred — GitHub Security Advisories**: open a private advisory in the affected repo (e.g. <https://github.com/beeping-io/beeping-core/security/advisories/new>)
2. 📧 **Alternative — Email**: `security@beeping.io`

> 📌 This is the **organization-level** security policy. It applies to all repos in `beeping-io` that don't override it with their own `SECURITY.md`.

When reporting, please include:

- 📝 A clear description of the vulnerability and its potential impact.
- 🔁 Steps to reproduce, including code snippets or PoC if possible.
- 🎯 Affected component(s) and version(s).
- 🛠️ Any suggested mitigation or fix you have in mind.
- 📞 Your preferred contact information for follow-up.

## ⏱️ Response timeline

| Stage | Target |
|---|---|
| Initial acknowledgment | Within **48 hours** |
| Triage and severity assessment | Within **7 days** |
| Fix development | Depends on severity (Critical/High = priority) |
| Public disclosure | Coordinated with reporter, **90 days** maximum from initial report |

## 🎯 Scope

This security policy covers all components of the Beeping Platform ecosystem:

- 📲 `beeply` (this repo) — Flutter reference app
- 🧱 `beeping-core` — C++ ultrasonic library
- 📡 `beepbox` — C++ HTTP service
- 🤖 `beeping-android` — Kotlin SDK
- 🍎 `beeping-ios` — Swift SDK
- 🔌 `beeping_flutter` — Flutter plugin
- 🌐 `beeping-web` — Web SDK family (WASM + React + Vue + Svelte + Vanilla)
- ⚛️ `beeping-react-native` — React Native plugin
- 🟢 `beeping-node` — Node.js server SDK
- 🐍 `beeping-python` — Python server SDK
- 🦀 `beeping-cli` — Rust CLI
- ☁️ `beeping-backend` — Firebase Functions backend
- 🎛️ `beeping-portal` — Developer console
- 🌐 `beeping-www` — Marketing site
- 📚 `beeping-docs` — Documentation site
- ☁️ `api.beeping.io` — Hosted Cloud service
- ☁️ `console.beeping.io` — Developer portal

## 🚫 Out of scope

- Issues in third-party dependencies (please report to the upstream maintainer first; we monitor via Renovate Bot and Dependabot)
- DoS attacks against `api.beeping.io` (rate limiting and Cloud Run autoscaling are designed to handle these)
- Findings from automated scanners without a clear exploit
- Reports from physical, social engineering, or insider threat attack vectors

## 🏆 Recognition

While we do **not** offer monetary bug bounties at this time, we maintain a public **Hall of Fame** for security researchers who responsibly disclose vulnerabilities.

When your report leads to a security advisory, you will be:

- 🏅 Credited in the published advisory (with your consent)
- 📝 Added to the Hall of Fame at `https://beeping.io/security/hall-of-fame` (post-launch)
- 🤝 Acknowledged in release notes when the fix ships

## 🛡️ Supported versions

| Version | Supported |
|---|---|
| `1.x` (latest) | ✅ Yes — security fixes backported |
| `0.x` (pre-release) | ✅ Yes during MVP development |
| Older versions | ❌ No |

## 🔐 Encryption

If you prefer to encrypt sensitive details, our PGP key for `security@beeping.io` will be published at `https://beeping.io/.well-known/security.txt` post-launch.

## 📚 Additional resources

- Beeping Platform [Privacy Policy](https://beeping.io/legal/privacy) (post-launch)
- Beeping Platform [Terms of Service](https://beeping.io/legal/terms) (post-launch)
- Beeping Platform [Sub-processors list](https://beeping.io/legal/sub-processors) (post-launch)

---

**Thank you for helping keep Beeping and our users safe.** 🙏
