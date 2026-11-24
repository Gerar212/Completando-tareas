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
# AGENTS.md — Completando-tareas

## Descripción del producto
**Completando-tareas** es una aplicación web enfocada en completar y cargar tareas de forma organizada, centralizando el registro, la carga de pendientes y el seguimiento de su estado.

## Entorno y puesta en marcha
Antes de ejecutar o modificar código, ten en cuenta el flujo estándar del proyecto:
- Levantar servicios: `docker compose up -d --wait`
- Migraciones: `npm run migrate`
- Datos iniciales: `npm run seed`
- Desarrollo: `npm run dev`

## Convenciones para agentes y colaboradores
- Mantener los cambios acotados a la tarea o issue correspondiente.
- Trabajar en ramas derivadas de `main` y fusionar mediante Pull Request con los checks de CI en verde.
- Documentar en `docs/PRD.md` las decisiones funcionales y la carpeta en `src/` asociada a cada funcionalidad.
- No exponer credenciales ni datos sensibles en el repositorio.
