# Security Policy

Kredex handles financial logic and smart contracts, so security reports are taken seriously. Thank you for helping keep our users safe.

## Supported versions

| Component | Status |
| :-- | :-- |
| `contracts` / `product` on `main` | ✅ Supported (currently deployed on **Stellar Testnet**) |
| Older commits and forks | ❌ Not supported |

> Kredex is currently on **Testnet**. No real funds are at risk, but we treat every report as if mainnet were live.

## Reporting a vulnerability

**Please do not open a public issue, discussion or pull request for security problems.**

Use **GitHub Private Vulnerability Reporting**:

1. Go to the **Security** tab of the affected repository ([product](https://github.com/kredex-org/product/security), [contracts](https://github.com/kredex-org/contracts/security), [docs](https://github.com/kredex-org/docs/security)).
2. Click **Report a vulnerability**.
3. Describe the issue and include as many of these as you can:
   - Affected repo, file, contract or function
   - Steps to reproduce or a proof of concept
   - Impact (who is affected, what can an attacker do)
   - Suggested fix, if any

If you cannot use GitHub reporting, send us a short direct message on X at [@kredexweb3](https://x.com/kredexweb3) asking for a private channel. **Do not post details publicly.**

## What to expect

| Step | Target time |
| :-- | :-- |
| Acknowledgement | within 3 days |
| Initial assessment | within 7 days |
| Fix or mitigation plan | depends on severity, and we will keep you updated |
| Public disclosure | coordinated with you after a fix is available |

## Scope

**In scope**
- Soroban contracts: `borrower_reputation`, `reputation_nft`, `lending`, `escrow`, `default_management`, `liquidity_pool`, `oracle_adapter`
- Authentication, session and authorization logic in the product
- KYC data handling and API routes
- Leaked secrets in any repository

**Out of scope**
- Social engineering or physical attacks
- Denial-of-service through volume or rate alone
- Issues in third-party services (Stellar network, Freighter, Vercel, Neon, Upstash). Report these to their owners.
- Findings that need a rooted device or an already-compromised account
- Missing best-practice headers with no demonstrated impact

## Safe harbor

If you act in good faith, avoid privacy violations and data destruction, only test against Testnet or your own deployment, and give us reasonable time to fix the issue before disclosure, we will not pursue action against you.

## Handling secrets

- Never commit `.env` files, private keys or Stellar secret keys (`S...`).
- If you find an exposed secret, report it privately as above. Do not use it.

## Recognition

We are happy to credit reporters in release notes (or keep you anonymous, your choice).
