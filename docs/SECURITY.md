# Security & Branch Protection Rules

## Branch Protection
- `main` is protected.
- CI must pass before merging.
- Only dev and QA leads can merge to `main`.
- PR review required (at least 1 approval)
- Enforce linear history

## Secrets & Credentials
- Never commit API keys.
- Use GitHub Secrets for sensitive information.

## Permissions
- Restrict write access to contributors as needed.
