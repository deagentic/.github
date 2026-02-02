# Contributing to Deagentic Projects

Thank you for your interest in contributing! We follow the "Deagentic Way".

## 1. Fork & Branch

- Fork the repository (if external) or create a branch (if internal).
- Branch names: `feat/my-feature`, `fix/my-bug`.

## 2. Environment Setup

Most Data Science projects use `kedro`.

```bash
pip install -r requirements.txt
pip install behave pre-commit
```

## 3. Code Standards

We use **Ruff** for linting and formatting.

```bash
ruff check .
ruff format .
```

Ensure all tests pass:

```bash
```bash
pytest
behave
```

## 4. Pre-commit Hooks

We use pre-commit to ensure consistency.

```bash
pip install pre-commit
pre-commit install
```

Now, every time you `git commit`, our checks will run automatically.

## 4. Commit Messages

Use [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation
- `test:` Adding tests

## 5. Submit PR

- Open a Pull Request against `main`.
- Fill out the PR template.
- Wait for CI checks to pass.
