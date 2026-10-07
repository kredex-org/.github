# Starter Issues

Ready-to-paste issues for maintainers. Create each in the named repo (use the *Good first issue* form), and add labels `good first issue`, `help wanted`, plus the difficulty and `area:` labels from [`labels.yml`](labels.yml).

## docs (`kredex-org/docs`)

| # | Title | Difficulty |
| :-: | :-- | :-- |
| 1 | Add a glossary page (Soroban, SEP-12, escrow, soulbound NFT, reputation tier) | beginner |
| 2 | Add a Troubleshooting page for wallet and Testnet problems | beginner |
| 3 | Add screenshots to the usage guide | beginner |
| 4 | Document each contract's functions on the implementation page | intermediate |
| 5 | Proofread all pages for typos and grammar | beginner |

## product (`kredex-org/product`)

| # | Title | Difficulty |
| :-: | :-- | :-- |
| 1 | Add a tooltip explaining how the trust score is calculated | beginner |
| 2 | Add accessible labels and focus states to dashboard forms | beginner |
| 3 | Add a light/dark theme toggle | intermediate |
| 4 | Reduce repeated questions in the KYC flow | intermediate |
| 5 | Add unit tests for helpers in `lib/` | intermediate |
| 6 | Show USDC/XLM currency consistently across lender pages | intermediate |
| 7 | Add loading skeletons to dashboard tables | beginner |
| 8 | Rename the legacy `trustlend_pending_role` storage key to a Kredex name, with a migration | advanced |

## contracts (`kredex-org/contracts`)

| # | Title | Difficulty |
| :-: | :-- | :-- |
| 1 | Add `///` doc comments to all public functions in `escrow` | beginner |
| 2 | Add unit tests for `oracle_adapter` | beginner |
| 3 | Add unit tests for `escrow` (hold, revoke window, confirm) | intermediate |
| 4 | Add unit tests for `lending` (lifecycle, overdue, default) | intermediate |
| 5 | Add unit tests for `liquidity_pool` and `reputation_nft` | intermediate |
| 6 | Fix `cargo fmt` differences and enable the format check as blocking in CI | beginner |
| 7 | Fix `cargo clippy` warnings (e.g. `too_many_arguments`) and make clippy blocking in CI | intermediate |
| 8 | Rename "TrustLend" leftovers in `scripts/deploy.*` to Kredex | beginner |
| 9 | Fuzz/property tests for interest calculation in `lending/src/interest_rate.rs` | advanced |

## .github (`kredex-org/.github`)

| # | Title | Difficulty |
| :-: | :-- | :-- |
| 1 | Add a first-PR walkthrough with screenshots to CONTRIBUTING | beginner |
| 2 | Add a workflow to sync labels from `labels.yml` | intermediate |
