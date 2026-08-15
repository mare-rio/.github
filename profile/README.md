<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mare-rio/.github/main/profile/assets/mare-rio-signature-ground-night.png">
  <img src="https://raw.githubusercontent.com/mare-rio/.github/main/profile/assets/mare-rio-signature-ground-day.png" alt="Maré Rio — Moana walking the sand, the wordmark set in sea water">
</picture>

A personal project by [Daniel Cavalli](https://github.com/danielcavalli), developed through
collaboration with AI agents: a portable, Kubernetes-native application platform and the products
built on it — notes, personal finance, and a learning library.

## How Maré is organized

Maré deliberately separates four kinds of truth:

- **[Architecture](https://github.com/mare-rio/mare-architecture)** records accepted cross-system
  design and why it was chosen.
- **[Work](https://github.com/mare-rio/mare-work)** records delivery order, current execution state,
  and exact evidence.
- **[Platform](https://github.com/mare-rio/mare-platform)** owns the portable product: runtime
  source, contracts, operators, packages, charts, CLI behavior, and releases.
- **[Infrastructure](https://github.com/mare-rio/mare-infra)** owns the concrete `dan.rio`
  environment: provisioning, release selection, desired state, operations, and live observations.

The [design system](https://github.com/mare-rio/mare-design-system) and each application own their
own product and source truth: [Notes](https://github.com/mare-rio/notes),
[Finance](https://github.com/mare-rio/finance), and
[Library](https://github.com/mare-rio/library).

Older Hub, chart, CLI, and SDK repositories are historical migration or retirement inputs. They
are not starting points for new platform or infrastructure work.

## How a platform change reaches `dan.rio`

These are separate, observable steps:

1. Source is reviewed and merged in its owning repository.
2. `mare-platform` publishes an immutable release.
3. `mare-infra` selects an exact release for `dan.rio`.
4. Argo CD reconciles that environment's desired state.
5. Live inspection proves what is actually running.

A merge is therefore not, by itself, proof of publication, environment selection, or live
deployment. This page is a reading map, not a second architecture or status authority.

<img src="https://raw.githubusercontent.com/mare-rio/.github/main/profile/assets/canon-01-shore-home.png" alt="the Shore — Maré's home surface: serif app names on a warm paper ground, a quiet tide line at the foot">
<p align="center"><em>the Shore — Maré's home surface, from the design canon</em></p>

## Project status

The working repositories are private while the project matures. Parts may be open-sourced
(Apache-2.0) when they are ready — as a gift, not a product. There is no company here, no
customers, and nothing for sale.
