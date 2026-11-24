# Completando-tareas

Completa y carga tareas.

## Puesta en marcha

1. Cambia `mi-producto` por el nombre de tu producto en `docker-compose.yml` (línea `name:`) y en `package.json` (`name`).
2. Levanta el proyecto ejecutando:

   ```bash
   docker compose up -d --wait
   npm run migrate
   npm run seed
   npm run dev
   ```
