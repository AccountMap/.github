# Contributing to AccountMap

Thanks for helping! This guide applies to every repository in the AccountMap organization unless a repository has its own `CONTRIBUTING.md`.

## Before you start

- **Look for an issue first.** Issues labeled [`good first issue`](https://github.com/AccountMap/accountmap/labels/good%20first%20issue) are a good place to begin. For anything bigger than a small fix, comment on the issue (or open one) before writing code, so we can agree on the approach.
- **Issues labeled `decision`** need a decision before work starts. Discussion is welcome there; code isn't yet.
- **Security problems are never reported in public issues.** See [SECURITY.md](SECURITY.md).

## Making a change

1. Fork the repository and create a branch from `main` (for example `fix/import-duplicates` or `feat/focus-view`).
2. Follow the setup instructions in that repository's README.
3. Keep pull requests focused on one change. Add or update tests for behaviour you change.
4. Make sure lint, typecheck, tests, and build pass locally; CI runs the same checks.
5. Open a pull request, fill in the template, and link the issue (`Closes #123`).

## Never use real data

AccountMap handles sensitive information about people's accounts. In issues, pull requests, screenshots, test fixtures, and logs, **use made-up data only**: no real email addresses, phone numbers, or account lists.

## Licensing and sign-off

The license and contributor terms (DCO sign-off or a CLA) are still being decided in [accountmap#1](https://github.com/AccountMap/accountmap/issues/1) and [accountmap#2](https://github.com/AccountMap/accountmap/issues/2). Until then, small contributions are welcome; larger ones may be asked to agree to the final terms once they're chosen.

## Code of conduct

Be kind and assume good intent. Harassment or personal attacks aren't tolerated in any AccountMap space.
