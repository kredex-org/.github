# Governance

Kredex is an open-source project run in the open. This document explains how decisions are made and how you can grow from contributor to maintainer.

## Principles

- **Open by default.** Discussion, decisions and roadmap live in public.
- **Merit and kindness.** Influence is earned through consistent, helpful contributions, and always within our [Code of Conduct](CODE_OF_CONDUCT.md).
- **Security first.** Anything touching funds, contracts, auth or KYC data gets extra scrutiny.

## Roles

| Role | How you get there | Responsibilities |
| :-- | :-- | :-- |
| **Community member** | Anyone | Use the product, ask questions, give feedback |
| **Contributor** | Have a merged PR (docs count!) | Submit issues and PRs, help others |
| **Reviewer / Triager** | Several quality contributions, invited by maintainers | Triage issues, review PRs, mentor newcomers |
| **Maintainer** | Sustained contributions and trust, nominated by existing maintainers | Merge PRs, cut releases, set direction, enforce the Code of Conduct |

See [MAINTAINERS.md](MAINTAINERS.md) for the current list.

## How decisions are made

1. **Small changes** (bug fixes, docs, refactors): one maintainer approval and passing CI.
2. **Larger changes** (new features, API or contract interface changes): open an issue or a *Ideas* discussion first. Allow at least 5 days for feedback, and get approval from at least two maintainers.
3. **Smart-contract changes**: always need two maintainer approvals and tests. Changes that alter on-chain state layout or deployed behavior also require a written migration/upgrade note.
4. **Disagreements**: we aim for consensus. If there is none, the maintainers decide by majority vote and document the reasoning in the issue.

## Becoming a maintainer

Maintainers invite contributors who have shown good judgment, reliability and care for the community. You can also ask in Discussions, and we'll tell you honestly what to work on next.

Maintainers who are inactive for 6+ months may be moved to **Emeritus** status, with thanks, and are welcome back at any time.

## Releases

- `main` is always deployable.
- Releases are tagged using [Semantic Versioning](https://semver.org/).
- Contract deployments to any network are announced in Discussions and recorded in the contracts repo.

## Changing this document

Open a pull request. Governance changes require approval from a majority of maintainers.
