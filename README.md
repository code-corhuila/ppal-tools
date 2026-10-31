# ppal-tools

Shared development tooling that may support the PantryPal repositories.

## Purpose

This repository is for project tooling and automation. It is not a deployed PantryPal service and is not required as a runtime dependency for the accepted mobile MVP unless a specific tool is approved and documented.

## Repository workflow

This repository uses develop for integration, qa for verification, and main for approved releases. Submit changes through a short-lived feat/, fix/, chore/, or docs/ branch and a pull request. Do not commit directly to protected branches or use force-push.

## Shared project governance

The authoritative scope, ADRs, API contract, and release process live in ppal-docs. Keep scripts, dependency versions, and usage instructions documented in English.

## Security

Never commit access tokens, credentials, keystores, environment files, or other secrets. Tooling that changes repositories or publishes artifacts must use the least privileges needed and be reviewed before use.
