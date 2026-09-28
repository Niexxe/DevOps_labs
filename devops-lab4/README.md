# Lab 4 — Docker Compose

This lab demonstrates a multi-container application orchestrated with Docker Compose.

## Services

- `api` — Python backend service.
- `db` — PostgreSQL database.
- `nginx` — Nginx serving the frontend build and acting as the web entry point.

## Structure

```text
backend/            Backend source code and Dockerfile
nginx/              Nginx configuration, frontend build and Dockerfile
docker-compose.yml  Multi-service Compose configuration
```

## Environment

Copy the example environment file before starting the stack:

```bash
cp backend/.env.example backend/.env
docker compose up --build
```

The local `.env` file is intentionally excluded from version control.
