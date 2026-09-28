# Lab 5 — CI/CD

This lab contains a Python application, automated tests, a Dockerfile and GitHub Actions workflows for continuous integration and image delivery.

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt pytest httpx
python -m pytest tests/
```

The repository-level workflows in `.github/workflows/` run the tests for this lab and build/push its Docker image after successful CI on `main`.
