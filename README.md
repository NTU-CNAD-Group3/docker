# CNAD docker-compose

## Description

This repo contains the docker-compose file to setup the local environment for CNAD.

For now, it contains the following services:

- Postgres
- Redis
- RabbitMQ
- Gateway Service
- Notification Service
- Auth Service

1. clone all the repo in the same folder
2. run `docker compose -f docker/docker-compose.yaml up -d`
3. run `docker compose -f docker/docker-compose.yaml down` to stop the services

```bash
docker compose -f docker/docker-compose.yaml up -d
```
