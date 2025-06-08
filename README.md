# Stack: n8n + Evolution API + PostgreSQL + Redis

Este stack está listo para deploy en Railway utilizando Docker Compose.

## Servicios incluidos

- PostgreSQL (base de datos para n8n y evolution)
- n8n (automatizaciones)
- Evolution API (autenticación y sesiones)
- Redis (cache)

## Deploy en Railway

1. Subí este repo a GitHub.
2. En Railway: "New Project" > "Deploy from GitHub Repo".
3. Railway detectará el Dockerfile y el docker-compose.yml.

> Si Railway da error de Nixpacks, este Dockerfile "dummy" lo fuerza a usar Docker Compose.
