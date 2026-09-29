<div align="center">

# Beeping

**Send data over sound.**

Open-source SDKs for ultrasonic data exchange between nearby devices.
No Bluetooth. No NFC. No QR codes. No internet. Just audio.

[![License](https://img.shields.io/badge/license-Apache_2.0-blue)](https://www.apache.org/licenses/LICENSE-2.0)
[![beeping.io](https://img.shields.io/badge/beeping.io-website-063045)](https://beeping.io)
[![Discussions](https://img.shields.io/badge/community-discussions-7C3AED)](https://github.com/beeping-io/.github/discussions)
[![Slack](https://img.shields.io/badge/Slack-join-4A154B?logo=slack&logoColor=white)](https://join.slack.com/t/beeping-io/shared_invite/zt-3yv2kc6qs-tWxx1AViHgdEembSPqm26Q)
[![Discord](https://img.shields.io/badge/Discord-join-5865F2?logo=discord&logoColor=white)](https://discord.gg/XNPXdZK7)

</div>

---

## The repositories

[**`beeping-core`**](https://github.com/beeping-io/beeping-core) — C++20 engine. Turns bytes into sound, and sound back into bytes. Every SDK calls into this.

[**`beepbox`**](https://github.com/beeping-io/beepbox) — HTTP server wrapping the engine as a REST API. Cloud mode for SDKs that don't want to ship the native engine.

[**`beeping-android`**](https://github.com/beeping-io/beeping-android) — Kotlin SDK. Local (JNI) + cloud (Ktor) dual mode.

[**`beeping-ios`**](https://github.com/beeping-io/beeping-ios) — Swift 6 SDK. Local (Objective-C++) + cloud (URLSession) dual mode.

Apache 2.0 across the platform.

---

## 🗺️ Market Roadmap & Ecosystem Validation Status

The Beeping ecosystem follows a rigorous Scientific Lean Validation framework (**E0 to E5**). Transition between stages is governed strictly by empirical quantitative Bayesian gates.

| Stage | Market Focus | Status | Progress | Remaining Work | Validation Gate |
|---|---|---|---|---|---|
| **E0** | **Problem Discovery** | ✅ Validated | `▓▓▓▓▓▓▓▓▓▓` 100% | 0 tasks | $N=5$ Blind problem interviews |
| **E1** | **Technical Feasibility (MVP)** | 🔄 In Progress | `▓▓▓▓▓░░░░░` 52% | 81 tasks (161 SP) | $p_0=1.00$ Physical hardware canary |
| **E2** | **Retention & Usability** | ⏳ Queued | `░░░░░░░░░░` 0% | 46 tasks (91 SP) | $p_0 \ge 0.60$ Unprompted return rate |
| **E3** | **Product-Market Fit** | ⏳ Queued | `░░░░░░░░░░` 0% | 170 tasks (322 SP) | $p_0 \ge 0.70$ External resource commitment |
| **E4** | **Channel & Growth** | ⏳ Queued | `░░░░░░░░░░` 0% | 67 tasks (131 SP) | $p_0 \ge 0.75$ Repeatable acquisition |
| **E5** | **Institutional Scale** | ⏳ Queued | `░░░░░░░░░░` 0% | 3 tasks (4 SP) | Proven unit economics |

### 🔬 Active Stage: `E1 · Technical Feasibility` Breakdown

| Milestone | Deliverable | Status |
|---|---|---|
| `E1 · 🧰 Dev Environment & Toolchains` | macOS workstation toolchains (Rust, Flutter, Conan, NDK) | ✅ Completed (28 SP) |
| `E1 · 🪜 Governance & Methodology` | Architectural rules, backlog triage, and Git hooks | ✅ Completed (32 SP) |
| `E1 · ✍️ Core Specs & Foundations` | Vision, Mission, P&L model, and Subprocessors register | ✅ Completed (13 SP) |
| `E1 · 🧱 Core DSP: C++20 Stability & Versioning` | Reed-Solomon overflow fix, ambient noise gate & dynamic versioning | 🔄 Active (7 SP) |
| `E1 · 🍎🤖 Native SDKs: iOS (Swift 6) & Android (Kotlin 2.0)` | Swift 6 actor concurrency, Kotlin 2.0/NDK r28 & 9-char cable | ⏳ Queued (9 SP) |
| `E1 · 🔌 Federated Flutter Plugin: Acoustic & Cloud` | Federated packages linking native iOS/Android engines | ⏳ Queued (22 SP) |
| `E1 · 📱 Flagship App: BeepDrop (Flutter)` | Ultrasonic P2P file & text sharing app with reactive logo vumeter | ⏳ Queued (21 SP) |
| `E1 · 🍎🤖 Native Sample Apps (SwiftUI & Compose)` | Standalone sample apps validating independent native SDKs | ⏳ Queued (8 SP) |
| `E1 · 🚀 SDK Distribution (CocoaPods, Maven, pub.dev)` | Production registry publication | ⏳ Queued (4 SP) |
| `E1 · 🌐 Web Portal & Ultrasonic Web Mixer` | `beeping.io` production deployment with WASM v0.8.1 & audio watermarking | ⏳ Queued (9 SP) |
| `E1 · 🎮 Web Playcenter: Acoustic Laboratories` | 35 browser-based acoustic labs (FFT Spectrogram, BER tester) | ⏳ Queued (77 SP) |

---

## Get involved

- 💬 [**Discussions**](https://github.com/beeping-io/.github/discussions) — ideas, Q&A, show-and-tell. Every category is readable without an account.
- 💼 [**Slack**](https://join.slack.com/t/beeping-io/shared_invite/zt-3yv2kc6qs-tWxx1AViHgdEembSPqm26Q) — real-time chat. Nine channels — one per SDK plus general, help, showcase, random.
- 🎮 [**Discord**](https://discord.gg/XNPXdZK7) — same nine channels, Discord flavour. Pick whichever client you already live in.
- 🐛 **Bugs** — file on the relevant repo above using the bug-report form.
- 🤝 [Contributing](https://github.com/beeping-io/.github/blob/main/CONTRIBUTING.md) · [Code of Conduct](https://github.com/beeping-io/.github/blob/main/CODE_OF_CONDUCT.md) · [Security](https://github.com/beeping-io/.github/blob/main/SECURITY.md)
- ✉️ Or email [hello@beeping.io](mailto:hello@beeping.io) — every message gets read.

---

<div align="center">

Listening for your signal.

</div>
