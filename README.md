# 🐍 python-sample

A simple Python Flask application containerized with Docker.  
CI/CD is integrated via GitHub Actions — images are automatically built and pushed to Docker Hub for each branch.

---

## 🚀 Project Overview

This repository includes:

- A minimal Flask web app (`app.py`)
- A `Dockerfile` for containerization
- GitHub Actions-based CI/CD workflows:
  - `main` branch → tagged as `:main`
  - `test` branch → tagged as `:test`

---

## 📦 Docker Hub

Docker images are published to:

👉 [codebynurgul/python-sample](https://hub.docker.com/r/codebynurgul/python-sample)

| Tag    | Description              |
|--------|--------------------------|
| `main` | Stable production build  |
| `test` | Development preview build |

---

## 🛠 Run Locally with Docker Compose

### 🧪 Test Environment

```bash
docker-compose -f docker-compose.test.yml up -d
