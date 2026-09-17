# First-Week Onboarding Checklist

Welcome to the team! Work through this checklist during your first week and check items off as you go. Your onboarding buddy and your manager are both here to help — don't hesitate to ask questions, no matter how small they seem.

## 1. Laptop Setup

- [ ] Unbox your laptop and complete the initial OS setup
- [ ] Install system updates and restart
- [ ] Set up full-disk encryption and a strong login password
- [ ] Enable the password manager and import your team vault
- [ ] Configure your password manager browser extension
- [ ] Familiarize yourself with the VPN client and confirm you can connect

## 2. Accounts and Access

- [ ] Log in to your company email and set up two-factor authentication
- [ ] Accept your GitHub organization invitation and enable SSO
- [ ] Add an SSH key (or configure your PAT) to your GitHub account
- [ ] Request access to the team's repositories from your manager
- [ ] Get access to the project tracking board (issues/epics)
- [ ] Join the team chat channels and the on-call rotation channel
- [ ] Verify access to the CI/CD dashboards and shared documentation

## 3. Dev Environment

- [ ] Install your package manager (Homebrew / apt, as appropriate)
- [ ] Install Git and configure `user.name` and `user.email`
- [ ] Clone the main service repository and run the setup script
- [ ] Install the recommended editor and the team's shared extensions/linters
- [ ] Get the local test suite running and confirm it is green
- [ ] Set up local environment variables using the example `.env` file
- [ ] Read through the README and the "Project Structure" section of the docs

## 4. Opening Your First Pull Request

- [ ] Create a feature branch from `main` (e.g. `add-onboarding-notes`)
- [ ] Make a small, self-contained change — fixing a typo in the docs is perfect
- [ ] Commit your change with a clear, descriptive message
- [ ] Push the branch and open a pull request against `main`
- [ ] Fill in the pull request template: what changed, why, and how to test it
- [ ] Request a review from your onboarding buddy
- [ ] Respond to review feedback and push follow-up commits
- [ ] Watch the CI checks pass before requesting re-review
- [ ] Merge the pull request once it is approved

## Tips for Your First Week

- It is completely fine to get stuck. Asking early is a strength, not a weakness.
- Keep notes as you learn — they often become great documentation PRs.
- This very repository is a live worked example of our pull-request workflow: look at its pull request and its merge commit on `main` to see the whole flow end to end.
