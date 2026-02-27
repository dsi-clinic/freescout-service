# freescout-service
FreeScout Docker Mirror Repo

This repository mirrors the official FreeScout Docker image into the internal Cloudflare container registry.

## Upstream Image

We currently use:

ghcr.io/tiredofit/docker-freescout:php8.3-1.17.146

## Database

FreeScout requires an external database. The FreeScout container does NOT include a database.
The database runs as a separate service.

Supported:
- MariaDB
- MySQL
- PostgreSQL
