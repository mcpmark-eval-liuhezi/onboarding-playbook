# Team Glossary

Short definitions of the terms we use constantly and always end up explaining to new folks. Additions are welcome — open a pull request!

## General

- **Playbook** — A repository that documents a process end to end, kept deliberately small and easy to skim. This repository is the onboarding playbook.
- **Buddy** — The teammate assigned to you for your first few weeks. Your first stop for any question, especially the ones that feel too small to ask.
- **On-call** — The engineer responsible for responding to production issues during a given rotation. New hires are always paired with an experienced teammate for their first rotation.

## Workflow

- **Feature branch** — A branch created from `main` where you do your work, usually named like `add-glossary-terms`.
- **PR (pull request)** — A proposal to merge a branch's changes into another branch. Our unit of code review and the primary way work lands in `main`.
- **Review request** — Explicitly asking specific teammates to review a PR. Do this once the PR is ready, not before.
- **LGTM** — "Looks good to me." A reviewer's shorthand approval signal; still requires the formal approve action on the PR.
- **Squash / rebase / merge commit** — The three ways GitHub can merge a PR. We use a regular **merge commit** for documentation PRs like this one, so the history keeps both the original commit and the merge itself.
- **Draft PR** — A PR opened before it's finished, to share work in progress and get early feedback.

## Engineering

- **Main (default branch)** — The branch we treat as always-deployable; all changes land here through PRs.
- **CI (continuous integration)** — The automated checks that run on every PR (build, tests, linters). A PR cannot merge while checks are red.
- **Green / red** — Informal status of the CI checks: green means everything passed, red means something failed.
- **Env vars** — Environment variables used for configuration. Never commit real secrets; copy the `.env.example` file and ask for values in the team channel.
- **Rollback** — Reverting a deployment to the previous known-good version. Boring, safe, and always preferred over hotfixes under pressure.
