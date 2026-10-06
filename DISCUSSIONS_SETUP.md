# Discussions Setup Kit

GitHub Discussions must be **enabled in settings** (this can't be done from files). Use this kit to set it up in a few minutes.

## 1. Enable Discussions

- **Org-level discussions** (recommended, lives in this `.github` repo): `.github` repo → **Settings → Features → Discussions** ✅. They appear at `github.com/orgs/kredex-org/discussions`.
- Also enable Discussions on `product`, `contracts` and `docs` if you want repo-specific threads.

## 2. Categories

| Category | Format | Description |
| :-- | :-- | :-- |
| 📣 Announcements | Announcement | Releases, deployments, news (maintainers only) |
| 🙏 Q&A | Question / Answer | Get help with setup and usage |
| 💡 Ideas | Open-ended | Propose and refine features |
| 🙌 Show and tell | Open-ended | Share what you built with Kredex |
| 🗺️ Roadmap | Open-ended | Discuss priorities and what's next |
| 🤝 Contributors lounge | Open-ended | Find teammates, ask for mentorship, coordinate work |
| 🔐 Security hardening | Open-ended | Public, non-sensitive security design talk (vulnerabilities go through [private reporting](SECURITY.md)) |

## 3. Welcome post (pin it, category: Announcements)

**Title:** 👋 Welcome to the Kredex community!

```markdown
Hi everyone, and welcome! 💙

Kredex is an open-source, on-chain reputation based P2P lending platform on Stellar. It's live on Testnet at https://kredex.vercel.app, and we're building the path to mainnet together.

**New here? Start with:**
- 📚 Docs: https://kredex-docs.vercel.app
- 🧭 Contributing guide: https://github.com/kredex-org/.github/blob/main/CONTRIBUTING.md
- 🌱 Good first issues: https://github.com/search?q=org%3Akredex-org+label%3A%22good+first+issue%22+state%3Aopen&type=issues
- 🗺️ Roadmap: https://github.com/kredex-org/.github/blob/main/ROADMAP.md

**Ways to take part**
- Ask anything in **Q&A**, there are no silly questions
- Pitch features in **Ideas**
- Introduce yourself below: who are you, what do you like building, and what would you like to learn?

Please be kind and follow our Code of Conduct. Follow us on X: https://x.com/kredexweb3
```

## 4. "Start here" post (pin it, category: Contributors lounge)

**Title:** 🧭 Where should I start contributing?

```markdown
Tell us your background and we'll point you to a good first task!

| You know... | Try... |
| --- | --- |
| Nothing about blockchain, just Markdown | docs repo: typos, clarity, new guides |
| React / Next.js / TypeScript | product repo: UI polish, accessibility, tests |
| Rust | contracts repo: tests, docs comments, gas/size improvements |
| Testing / writing | Try the Testnet app and report bugs or UX issues |

Reply with your skills and interests, and a maintainer or fellow contributor will help you pick something.
```

## 5. Introductions thread

**Title:** 🙋 Introduce yourself!
Body: "Say hi! Share your name or handle, where you're from, what you work on and what you'd like to learn."

## 6. Moderation tips

- Convert actionable ideas into issues and link both ways.
- Mark helpful Q&A answers to build a searchable knowledge base.
- Use the labels from [`labels.yml`](labels.yml).
