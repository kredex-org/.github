# Contributing to Kredex

Thank you for your interest in Kredex! 💙 Whether this is your first open-source contribution or your five-hundredth, you are welcome here. This guide applies to every repository in the [Kredex Org](https://github.com/kredex-org). Each repo also has its own `CONTRIBUTING.md` with setup details.

## Table of contents

- [Ways to contribute](#ways-to-contribute)
- [Your first contribution (step by step)](#your-first-contribution-step-by-step)
- [Which repo should I pick?](#which-repo-should-i-pick)
- [Finding something to work on](#finding-something-to-work-on)
- [Commit messages](#commit-messages)
- [Pull request checklist](#pull-request-checklist)
- [Review process](#review-process)
- [Getting help](#getting-help)
- [Security issues](#security-issues)
- [License](#license)

## Ways to contribute

You do **not** need to write code to help:

| Type | Examples |
| :-- | :-- |
| 📝 Documentation | Fix typos, improve explanations, add examples and tutorials |
| 🐛 Bug reports | Reproduce and report issues with clear steps |
| 🧪 Testing | Try the app on Stellar Testnet and report your experience |
| 🎨 Design / UX | Suggest or build UI improvements and accessibility fixes |
| 💻 Code | Fix bugs, build features, add tests |
| 🦀 Smart contracts | Improve Soroban contracts, write tests, review logic |
| 🔐 Security review | Responsibly disclose vulnerabilities |
| 💬 Community | Answer questions in [Discussions](https://github.com/orgs/kredex-org/discussions) |

## Your first contribution (step by step)

New to Git or GitHub? This is the whole flow.

1. **Find or open an issue.** Comment on it ("I'd like to work on this") so nobody duplicates the effort. For anything larger than a small fix, wait for a maintainer to confirm.
2. **Fork** the repository using the *Fork* button at the top right of the repo page.
3. **Clone your fork:**
   ```bash
   git clone https://github.com/<your-username>/<repo>.git
   cd <repo>
   git remote add upstream https://github.com/kredex-org/<repo>.git
   ```
4. **Create a branch** from an up-to-date `main`:
   ```bash
   git checkout main
   git pull upstream main
   git checkout -b fix/short-description
   ```
5. **Make your change.** Follow the repo's `CONTRIBUTING.md` for setup, linting and tests.
6. **Commit** using [Conventional Commits](#commit-messages):
   ```bash
   git add .
   git commit -m "docs: clarify wallet setup steps"
   ```
7. **Push and open a Pull Request:**
   ```bash
   git push origin fix/short-description
   ```
   Then click **Compare & pull request** on GitHub and fill in the template.
8. **Respond to review.** Push more commits to the same branch and the PR updates automatically.

> 💡 Never done this before? [First Contributions](https://github.com/firstcontributions/first-contributions) is a friendly practice repo, and [GitHub's guide to forking](https://docs.github.com/en/get-started/quickstart/fork-a-repo) explains the same flow.

## Which repo should I pick?

| If you know... | Start with |
| :-- | :-- |
| Nothing about blockchain yet | [docs](https://github.com/kredex-org/docs) (Markdown/MDX) |
| React, Next.js, TypeScript, SQL | [product](https://github.com/kredex-org/product) |
| Rust | [contracts](https://github.com/kredex-org/contracts) |

## Finding something to work on

Search across the whole org:

- 🌱 [`good first issue`](https://github.com/search?q=org%3Akredex-org+label%3A%22good+first+issue%22+state%3Aopen&type=issues): small, well-scoped, mentors available
- 🙋 [`help wanted`](https://github.com/search?q=org%3Akredex-org+label%3A%22help+wanted%22+state%3Aopen&type=issues): bigger tasks we'd love help with

Our difficulty labels: `difficulty: beginner`, `difficulty: intermediate`, `difficulty: advanced`.

Have an idea? Start a thread under **Ideas** in [Discussions](https://github.com/orgs/kredex-org/discussions) before building something big, so we can align on direction.

## Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(optional scope): <short summary>
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`.

Examples:
- `feat(lending): add early repayment support`
- `fix(dashboard): copy wallet address on click`
- `docs: add Freighter troubleshooting section`

## Pull request checklist

- [ ] The PR is focused: one logical change
- [ ] It links an issue (`Closes #123`) when one exists
- [ ] The code builds, lints and passes tests (see the repo's CONTRIBUTING)
- [ ] I added or updated tests and docs where relevant
- [ ] **No secrets, keys, `.env` files or personal data** are included
- [ ] Screenshots are attached for UI changes

## Review process

1. A maintainer will respond to your PR, usually within **3-5 days**. Feel free to nudge politely after a week.
2. We may request changes. This is normal and not a rejection.
3. CI must pass and at least one maintainer must approve.
4. We squash-merge to keep history clean. You'll be credited as the author.

## Getting help

Stuck? Don't struggle alone:

- Ask in [Discussions → Q&A](https://github.com/orgs/kredex-org/discussions)
- Comment on the issue you are working on
- Reach us on X: [@kredexweb3](https://x.com/kredexweb3)

There are no silly questions here.

## Security issues

**Do not open a public issue for vulnerabilities.** See our [Security Policy](SECURITY.md).

## License

By contributing, you agree that your contributions are licensed under the **MIT License** of the repository you contribute to.

Please also follow our [Code of Conduct](CODE_OF_CONDUCT.md).
