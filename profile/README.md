<div align="center">

# 🔊 Beeping

**Data over sound.**

_No NFC. No QR codes. No internet. Just audio._

[![License](https://img.shields.io/badge/license-Apache_2.0-blue?style=for-the-badge)](https://opensource.org/licenses/Apache-2.0)
[![Status](https://img.shields.io/badge/status-early_development-orange?style=for-the-badge)](https://beeping.io)
[![Website](https://img.shields.io/badge/website-beeping.io-063045?style=for-the-badge)](https://beeping.io)

</div>

---

## 🧩 The idea

Beeping is an **open source developer platform** for sending data between
nearby devices using audible or ultrasonic sound.

Two phones. One plays a beep. The other listens. The message arrives.

No NFC. No QR. No internet. Just audio.

---

## 🎭 The cast

Beeping isn't one project — it's a cast of components that pass a signal
around, each doing one thing well.

### 🎙️🎧 The core

Turns bytes into sound. And sound back into bytes.
The C++ library every SDK calls into.
_v0.0.0 released — both directions working._
Lives at [`beeping-core`](https://github.com/beeping-io/beeping-core).

### ☁️ The services

The cloud side — an HTTP server wrapping the core.
Live on Cloud Run. Encode and decode behind an API key during private alpha.
Health and version endpoints are public — `curl /version` to see it running.
Lives at [`beeping-io/beepbox`](https://github.com/beeping-io/beepbox).

### 🌐 The web

The front door. Where the story gets told, developers sign up, and the
project gets a face.
_Early days — you're reading it._
Lives at [`beeping-www`](https://github.com/beeping-io/beeping-www).

---

## 🔮 What's next

Not yet real, but coming.

- 🔌 **The SDKs** — language wrappers so you can call the core from your
  app: Swift, Kotlin, Flutter, React Native, JS, Python, Rust.
- 📱 **The app** — a Flutter reference where humans actually use all
  this to send contacts, links and files over sound.

No dates. It ships when it ships.

---

## 🤝 Want to help shape it?

The project is at day one. The way you help depends on what time you have.

- ⭐ **Star the repos you want to follow.** That's how we know who's watching.
- 💬 **Open an issue** in the relevant repo or start a
  [discussion](https://github.com/orgs/beeping-io/discussions). Questions,
  ideas, bug reports — all welcome.
- 🛠️ **Pick a task.** Look for `good-first-issue` labels across our repos.
- ✉️ **Write back.** If you got a welcome email, just reply. Otherwise
  write to [alfred@beeping.io](mailto:alfred@beeping.io). Every message
  gets read.

---

## 🛠️ Dev tools we've shipped

Small utilities that popped out of the project and got open-sourced
immediately, usable by anyone:

- [`@beeping.io/commitlint-config`](https://www.npmjs.com/package/@beeping.io/commitlint-config)
  — shared conventional commits config for the ecosystem.

---

## 📜 License

Everything here is [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
unless explicitly stated otherwise.

---

<div align="center">

**Listening for your signal.**
_— The Beeping team_

[🌐 beeping.io](https://beeping.io)

</div>
