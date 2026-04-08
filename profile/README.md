<div align="center">

# 🔊 Beeping

**Open source platform for ultrasonic data exchange between nearby devices.**

_No NFC. No QR. No internet required._

[![Website](https://img.shields.io/badge/website-beeping.io-7C3AED?style=for-the-badge)](https://beeping.io)
[![Docs](https://img.shields.io/badge/docs-docs.beeping.io-2F80ED?style=for-the-badge)](https://docs.beeping.io)
[![Status](https://img.shields.io/badge/status-early_development-orange?style=for-the-badge)](https://status.beeping.io)
[![License](https://img.shields.io/badge/license-Apache_2.0-blue?style=for-the-badge)](https://opensource.org/licenses/Apache-2.0)

</div>

---

## 🧩 What is Beeping?

Beeping is an **open source developer platform** that lets any application exchange data between nearby devices using **ultrasonic sound** — without NFC, QR codes, or internet connectivity.

Built for developers, by developers. **Cloud + Local mode** in every SDK. **18 repos**, all Apache-2.0.

---

## 🚀 Get started in 5 minutes

```bash
# Pick your stack:
flutter pub add beeping_flutter            # 🔌 Flutter
npm install @beeping/react-native           # ⚛️ React Native
npm install @beeping/react @beeping/web    # 🌐 React + WASM
npm install @beeping/vue @beeping/web      # 🟢 Vue + WASM
npm install @beeping/svelte @beeping/web   # 🟧 Svelte + WASM
npm install @beeping/node                  # 🟢 Node.js
pip install beeping                         # 🐍 Python
brew install beeping-io/tap/beeping         # 🦀 CLI
```

```kotlin
// 🤖 Android (Kotlin)
implementation("io.beeping:beeping-android:1.0.0")
```

```swift
// 🍎 iOS (Swift Package Manager)
.package(url: "https://github.com/beeping-io/beeping-ios", from: "1.0.0")
```

→ **Full quickstarts**: <https://docs.beeping.io/quickstart>

---

## 🌐 The ecosystem

| 🧱 Core | 📡 Service | 📱 Mobile | 🌐 Web |
|---|---|---|---|
| [`beeping-core`](https://github.com/beeping-io/beeping-core) — C++20 library | [`beepbox`](https://github.com/beeping-io/beepbox) — HTTP service | [`beeping-android`](https://github.com/beeping-io/beeping-android) — Kotlin SDK | [`beeping-web`](https://github.com/beeping-io/beeping-web) — WASM monorepo |
| | | [`beeping-ios`](https://github.com/beeping-io/beeping-ios) — Swift SDK | • `@beeping/web` (core) |
| | | [`beeping_flutter`](https://github.com/beeping-io/beeping_flutter) — Flutter plugin | • `@beeping/react` |
| | | [`beeping-react-native`](https://github.com/beeping-io/beeping-react-native) — RN plugin | • `@beeping/vue` |
| | | | • `@beeping/svelte` |
| | | | • `@beeping/vanilla` |

| ⚙️ Server | 🛠️ Tools | ☁️ Cloud | 📚 Docs & Apps |
|---|---|---|---|
| [`beeping-node`](https://github.com/beeping-io/beeping-node) — Node.js SDK | [`beeping-cli`](https://github.com/beeping-io/beeping-cli) — Rust CLI | [`beeping-backend`](https://github.com/beeping-io/beeping-backend) — Firebase Functions | [`beeping-docs`](https://github.com/beeping-io/beeping-docs) — Astro docs |
| [`beeping-python`](https://github.com/beeping-io/beeping-python) — Python SDK | | [`beeping-portal`](https://github.com/beeping-io/beeping-portal) — Dev console | [`beeping-www`](https://github.com/beeping-io/beeping-www) — Marketing site |
| | | | [`beeply`](https://github.com/beeping-io/beeply) — Flutter reference app |
| | | | [`beeply-rn`](https://github.com/beeping-io/beeply-rn) — RN reference app |
| | | | [`beeply-web`](https://github.com/beeping-io/beeply-web) — Web reference app |

→ **Architecture, ADRs and IaC**: [`beeping-meta`](https://github.com/beeping-io/beeping-meta)

---

## ✨ Features

- ☁️🔌 **Dual mode**: hosted Cloud API or fully on-device Local mode in every SDK — same public API
- 🌐 **12+ stacks**: iOS, Android, Flutter, React Native, React, Vue, Svelte, Vanilla JS, Node, Python, Rust CLI, raw HTTP API
- 🛡️ **Privacy-first**: zero third-party trackers, structured logs with PII redaction, GDPR-ready DPA
- 📊 **First-party analytics**: developers consume their own usage stats from the dev console
- 🧪 **Tested obsessively**: 14 testing strata, ≥90% coverage required, mutation testing where it matters
- 🔏 **Supply chain blindado**: cosign keyless (Sigstore) + SBOM CycloneDX + SLSA L3 provenance
- 🌍 **i18n EN+ES** from day one in all customer-facing surfaces

---

## 🍳 Use cases (cookbooks)

- 📇 Exchange contact cards at conferences (vCard handoff)
- 🎫 Conference badge pairing
- 🛒 In-store coupons via store speakers
- 📺 TV ad → app action (audio watermark)
- 🔐 Proximity-based 2FA
- 🏪 POS / kiosk → mobile handoff
- 🎮 Local multiplayer device pairing
- 📡 IoT device pairing (no Wi-Fi credential exchange)

→ **Full cookbook**: <https://docs.beeping.io/cookbooks>

---

## 🏗️ Status

> 🚧 **Early development.** The platform is being built in public, phase by phase.
>
> Public release of `v1.0.0` targeted for **May 2027**.
>
> Follow the **public roadmap** in the [Beeping platform Linear project](https://linear.app/beeping/project/beeping-platform-03da887d924e) (read-only after launch) or in the [`beeping-meta` repo](https://github.com/beeping-io/beeping-meta/blob/main/ROADMAP.md) (post Phase 0).

---

## 🤝 Contributing

We welcome contributions of all kinds — code, docs, translations, bug reports, feature requests, security disclosures.

- 🐛 **Bug reports**: open an issue in the relevant repo
- ✨ **Feature requests**: same
- 🛡️ **Security vulnerabilities**: <security@beeping.io> (do **not** open a public issue) — see [`SECURITY.md`](SECURITY.md)
- 💬 **Questions and discussions**: [GitHub Discussions](https://github.com/orgs/beeping-io/discussions)

→ **Full contributing guide**: [`CONTRIBUTING.md`](CONTRIBUTING.md)

---

## 📜 License

Everything in the Beeping organization is licensed under [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0) unless explicitly stated otherwise.

```text
Copyright 2026 Beeping Contributors

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
```

---

<div align="center">

**Made with 🔊 in the open. Star us on GitHub if you find Beeping useful.**

[🌐 beeping.io](https://beeping.io) · [📚 docs.beeping.io](https://docs.beeping.io) · [🚦 status.beeping.io](https://status.beeping.io)

</div>
