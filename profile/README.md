<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mare-rio/.github/main/profile/assets/mare-rio-signature-ground-night.png">
  <img src="https://raw.githubusercontent.com/mare-rio/.github/main/profile/assets/mare-rio-signature-ground-day.png" alt="Maré Rio — Moana walking the sand, the wordmark set in sea water">
</picture>

A personal project by [Daniel Cavalli](https://github.com/danielcavalli): a small, Kubernetes-native
application platform (the **Hub**) and the apps that run on it — notes, personal finance, a learning
library — built end-to-end by one human directing AI agents.

## What lives here

- **The platform** — an API gateway, Kubernetes operators, and a web shell that give every app
  auth, tenancy, database routing, migrations, realtime, and deploys for free.
- **SDKs** — a Python backend SDK and a TypeScript front-end SDK that define the app contract,
  plus a CLI that scaffolds new apps with the contract already wired.
- **Maré** — the design system: tokens, CSS, React, and a soul. Every surface is judged by a
  critic with taste before it ships.
- **The apps themselves** — each one a small, deterministic tool for everyday life.

Everything deploys by GitOps: merge to `main` → Argo CD → a k3s cluster.

<img src="https://raw.githubusercontent.com/mare-rio/.github/main/profile/assets/canon-01-shore-home.png" alt="the Shore — Maré's home surface: serif app names on a warm paper ground, a quiet tide line at the foot">
<p align="center"><em>the Shore — Maré's home surface, from the design canon</em></p>

## Status

The repositories are private while the project matures. Parts of it may be open-sourced
(Apache-2.0) when they are ready — as a gift, not a product: there is no company here,
no customers, and nothing for sale.
