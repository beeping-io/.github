# 🤝 Contributing to Beeping

Thank you for your interest in contributing to the **Beeping Platform**! 🎉

This document is the **organization-level** contributing guide. Individual repos may have their own `CONTRIBUTING.md` with stack-specific instructions — when present, follow the repo-specific one.

> 📌 Read first: [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md). By participating you agree to abide by it.

---

## 🎯 Ways to contribute

| Type | Where |
|---|---|
| 🐛 Bug reports | Open an issue in the relevant repo (use the bug template) |
| ✨ Feature requests | Open an issue in the relevant repo (use the feature template) |
| ❓ Questions | [Org-wide GitHub Discussions](https://github.com/orgs/beeping-io/discussions) |
| 🛡️ Security vulnerabilities | <security@beeping.io> — see [`SECURITY.md`](SECURITY.md) |
| 📚 Documentation improvements | PRs welcome on `beeping-docs` or any repo's `docs/` |
| 💻 Code contributions | PRs welcome — see workflow below |
| 🌍 Translations | EN + ES are core; other locales welcome |

---

## 🌐 The 18-repo ecosystem

Each repo has a clear scope. Pick the right one for your contribution:

- 🧱 [`beeping-core`](https://github.com/beeping-io/beeping-core) — C++ ultrasonic library
- 📡 [`beepbox`](https://github.com/beeping-io/beepbox) — C++ HTTP service
- 🤖 [`beeping-android`](https://github.com/beeping-io/beeping-android) — Kotlin SDK
- 🍎 [`beeping-ios`](https://github.com/beeping-io/beeping-ios) — Swift SDK
- 🔌 [`beeping_flutter`](https://github.com/beeping-io/beeping_flutter) — Flutter plugin
- 🌐 [`beeping-web`](https://github.com/beeping-io/beeping-web) — WASM monorepo (web/react/vue/svelte/vanilla)
- ⚛️ [`beeping-react-native`](https://github.com/beeping-io/beeping-react-native) — RN plugin
- 🟢 [`beeping-node`](https://github.com/beeping-io/beeping-node) — Node.js SDK
- 🐍 [`beeping-python`](https://github.com/beeping-io/beeping-python) — Python SDK
- 🦀 [`beeping-cli`](https://github.com/beeping-io/beeping-cli) — Rust CLI
- ☁️ [`beeping-backend`](https://github.com/beeping-io/beeping-backend) — Firebase Functions
- 🎛️ [`beeping-portal`](https://github.com/beeping-io/beeping-portal) — Dev console
- 🌐 [`beeping-www`](https://github.com/beeping-io/beeping-www) — Marketing site
- 📚 [`beeping-docs`](https://github.com/beeping-io/beeping-docs) — Documentation
- 📲 [`beeply`](https://github.com/beeping-io/beeply) — Flutter reference app
- 📱 [`beeply-rn`](https://github.com/beeping-io/beeply-rn) — RN reference app
- 🌍 [`beeply-web`](https://github.com/beeping-io/beeply-web) — Web reference app
- 🌱 [`beeping-meta`](https://github.com/beeping-io/beeping-meta) — Architecture, ADRs, IaC

---

## 📝 Standards across all repos

### License

Everything is licensed under **Apache License 2.0**. By contributing, you agree your contributions will be licensed under the same terms.

### Commit conventions

All repos use [**Conventional Commits**](https://www.conventionalcommits.org/) enforced by `commitlint`. Allowed types:

`feat` · `fix` · `docs` · `style` · `refactor` · `perf` · `test` · `build` · `ci` · `chore` · `revert`

### Branch model

- `develop` — default branch, all work merges here via PR
- `main` — release branch, only `release-please` PRs merge here
- `feature/*`, `fix/*`, etc. — work branches

Both `develop` and `main` are protected: PR + 1 review + linear history + no force pushes + no deletions.

### Definition of Done

Any contribution should meet the following before merging:

- ✅ Tests pass (≥ 90% line coverage / ≥ 85% branch coverage where applicable)
- ✅ Static analysis clean (lint + format + analyzer)
- ✅ Structured logging on new code paths
- ✅ Documentation updated
- ✅ CI green
- ✅ PR review approved

### Releases

Automated via [release-please](https://github.com/googleapis/release-please) in every repo. Versions and CHANGELOGs are computed from commit messages.

---

## 🚀 PR workflow

1. 🍴 Fork the repo (or create a branch if you have access)
2. 🌿 Create a branch from `develop`: `git checkout -b feat/your-feature`
3. 💻 Make your changes (small, focused commits with Conventional Commits format)
4. 🧪 Run tests locally
5. 📤 Push your branch
6. 🚀 Open a PR to `develop` using the PR template
7. 🤖 Wait for CI green
8. 👀 Address review comments
9. ✅ Merge (squash + delete branch is the standard merge strategy)

---

## 🛠️ Setting up your dev environment

Each repo has its own setup instructions. Common requirements:

- 🐙 **GitHub CLI** (`gh`) authenticated
- 🪝 **lefthook** for Git hooks: `brew install lefthook`
- 🛡️ **gitleaks**: `brew install gitleaks`
- 📝 **markdownlint-cli**: `brew install markdownlint-cli`
- 📦 **commitlint**: `npm install -g @commitlint/cli @commitlint/config-conventional`

Stack-specific (per repo):

- 🧱 **C++** (`beeping-core`, `beepbox`): CMake 3.25+, Conan 2, C++20 compiler
- 🤖 **Android**: Android Studio + SDK 35 + NDK r27
- 🍎 **iOS**: Xcode 16+ (macOS only)
- 🐦 **Flutter**: Flutter 3.24+
- 📦 **Node**: Node 22 LTS + pnpm
- 🐍 **Python**: Python 3.12 + uv
- 🦀 **Rust**: Rust 2024 edition (stable)

---

## 🤔 Where to find help

| Question | Where to look |
|---|---|
| How does Beeping work? | <https://docs.beeping.io> (post-launch) |
| What are the deadlines? | Public ROADMAP per repo |
| What's the architecture? | [`beeping-meta`](https://github.com/beeping-io/beeping-meta) |
| Where do I report security issues? | [`SECURITY.md`](SECURITY.md) — never as a public issue |
| How do I contact the team? | <https://github.com/orgs/beeping-io/discussions> |

---

## 🙏 Thank you

Every contribution — no matter how small — helps make Beeping better. We appreciate you taking the time to contribute. 🎉
