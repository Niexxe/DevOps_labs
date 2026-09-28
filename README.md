# DevOps Labs

A collection of practical DevOps laboratory exercises consolidated into a single repository. The labs cover Git fundamentals, Docker, Docker Compose, automated testing and CI/CD with GitHub Actions.

## Repository structure

| Directory | Topic | Main technologies |
| --- | --- | --- |
| `lab2_git/` | Git fundamentals | Git, GitLab CI configuration |
| `docker_lab3/` | Containerization | Docker, Java, Python |
| `devops-lab4/` | Multi-container applications | Docker Compose, Nginx, PostgreSQL, Python |
| `devops-lab5/` | CI/CD and testing | Python, Pytest, Docker, GitHub Actions |

## Labs

### Lab 2 — Git

Exercises covering Git repository structure and common version-control operations.

### Lab 3 — Docker

Containerization exercises using Java and Python applications.

### Lab 4 — Docker Compose

A multi-service stack consisting of a backend API, PostgreSQL database and Nginx frontend service orchestrated with Docker Compose.

### Lab 5 — CI/CD

A Python application with automated tests and repository-level GitHub Actions workflows for testing and Docker image delivery.

## Security and repository hygiene

Local environment files, virtual environments, caches, build artifacts and nested Git metadata are excluded from the repository. Use committed `.env.example` files as templates and keep real credentials in local environment files or GitHub Actions secrets.
