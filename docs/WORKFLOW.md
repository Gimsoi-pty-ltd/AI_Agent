# CI/CD Workflow

1. Developer creates a feature branch (`feature/xyz`).
2. Opens a PR to `dev`.
3. CI pipeline runs (checks code, runs tests).
4. Reviewer approves PR.
5. Merge to `dev`.
6. QA testing on `dev`.
7. Merge to `main` after QA approval.
8. Deployment triggers automatically to staging/production.
