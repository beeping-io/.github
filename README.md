# `beeping-io/.github`

This repository contains **organization-level community health files** for the [Beeping](https://beeping.io) GitHub organization. These files apply to **all repositories** in `beeping-io` that don't override them with their own copy.

## 📁 Contents

| File | Purpose | Visible at |
|---|---|---|
| `profile/README.md` | Organization profile shown publicly on GitHub | <https://github.com/beeping-io> |
| `CODE_OF_CONDUCT.md` | Contributor Covenant 2.1 — applies to all org repos by default | Each repo's "About" tab |
| `SECURITY.md` | Security disclosure policy — applies to repos without their own | Each repo's "Security" tab |
| `CONTRIBUTING.md` | General contribution guide for the organization | Each repo's PR template |
| `.github/FUNDING.yml` | Sponsorship configuration shown on every repo | "Sponsor" button |
| `.github/ISSUE_TEMPLATE/config.yml` | Default issue template config (contact links) | Each repo's "New issue" page |

## 🌐 Beeping ecosystem

This is **one of 18 repositories** that make up the Beeping platform. See the [organization profile](https://github.com/beeping-io) for the full ecosystem map.

## 🤖 How GitHub uses this repo

GitHub automatically picks up community health files from the `.github` repository at the **organization level**. Individual repos can override any file by providing their own copy.

For example:
- `beeping-io/beeply` provides its own `SECURITY.md` → its security policy applies for that repo
- `beeping-io/some-repo-without-security` falls back to this repo's `SECURITY.md`

This is the **GitHub-recommended pattern** for organizations that want consistent community health files across many repos without duplication.

## 📜 License

The contents of this repository are licensed under the [Apache License 2.0](LICENSE).

---

> 🚧 **Note**: This repo holds **community standards only**, not code. For development, see the individual project repositories listed in the [organization profile](https://github.com/beeping-io).
