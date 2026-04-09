# localstack

> Click To Deploy LocalStack — AWS Cloud Emulator

[![Sync](https://github.com/opensaasapps/localstack/actions/workflows/sync.yml/badge.svg)](https://github.com/opensaasapps/localstack/actions/workflows/sync.yml) [![Docker](https://github.com/opensaasapps/localstack/actions/workflows/docker.yml/badge.svg)](https://github.com/opensaasapps/localstack/actions/workflows/docker.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/thefractionalpm/localstack)](https://hub.docker.com/r/thefractionalpm/localstack)

Upstream: [localstack/localstack](https://github.com/localstack/localstack) · Auto-synced daily

---

## One-Command Deploy

```bash
cp .env.example .env && nano .env
docker compose up -d
```

## Coolify / Dokploy

1. New service → **Docker Compose**
2. Paste `docker-compose.yml`
3. Set env vars in UI
4. Deploy

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| `SERVICES` | ⚪ | |
| `DEBUG` | ⚪ | |
| `DOCKER_HOST` | ⚪ | |

## Image

```
docker pull localstack/localstack:latest
docker pull thefractionalpm/localstack:latest
```

## Ports

| Port | Service |
|---|---|
| `4566` | Main app |

---

*Part of the [OpenSaaSApps](https://github.com/opensaasapps) Click-To-Deploy collection.*
