# Branching Strategy Guide

## GitHub Flow (Recommended for this lab)
1. `main` is always deployable.
2. Create a feature branch from `main`: `git checkout -b feature/your-feature`
3. Make commits on the feature branch.
4. Open a Pull Request when ready.
5. Review and merge into `main`.

## Git Flow (Alternative)
- `main` – production
- `develop` – integration
- `feature/*` – new features
- `release/*` – release preparation
- `hotfix/*` – urgent fixes

## Practice Tasks
- Create a feature branch
- Push it and open a PR
- Simulate a code review
