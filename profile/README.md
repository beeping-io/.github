<div align="center">

# Beeping

**Send data over sound.**

Open-source SDKs for ultrasonic data exchange between nearby devices.
No Bluetooth. No NFC. No QR codes. No internet. Just audio.

[![License](https://img.shields.io/badge/license-Apache_2.0-blue)](https://www.apache.org/licenses/LICENSE-2.0)
[![beeping.io](https://img.shields.io/badge/beeping.io-website-063045)](https://beeping.io)
[![Discussions](https://img.shields.io/badge/community-discussions-7C3AED)](https://github.com/beeping-io/.github/discussions)

</div>

---

## The repositories

[**`beeping-core`**](https://github.com/beeping-io/beeping-core) — C++20 engine. Turns bytes into sound, and sound back into bytes. Every SDK calls into this.

[**`beepbox`**](https://github.com/beeping-io/beepbox) — HTTP server wrapping the engine as a REST API. Cloud mode for SDKs that don't want to ship the native engine.

[**`beeping-android`**](https://github.com/beeping-io/beeping-android) — Kotlin SDK. Local (JNI) + cloud (Ktor) dual mode.

[**`beeping-ios`**](https://github.com/beeping-io/beeping-ios) — Swift 6 SDK. Local (Objective-C++) + cloud (URLSession) dual mode.

Apache 2.0 across the platform.

---

## Get involved

- 💬 [**Discussions**](https://github.com/beeping-io/.github/discussions) — ideas, Q&A, show-and-tell. Every category is readable without an account.
- 🐛 **Bugs** — file on the relevant repo above using the bug-report form.
- 🤝 [Contributing](https://github.com/beeping-io/.github/blob/main/CONTRIBUTING.md) · [Code of Conduct](https://github.com/beeping-io/.github/blob/main/CODE_OF_CONDUCT.md) · [Security](https://github.com/beeping-io/.github/blob/main/SECURITY.md)
- ✉️ Or email [alfred@beeping.io](mailto:alfred@beeping.io) — every message gets read.

---

<div align="center">

Listening for your signal.

</div>
