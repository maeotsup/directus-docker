# Directus docker setup using Postgres db and Redis cache

Before starting change ADMIN_EMAIL and ADMIN_PASSWORD to your preferred values in the `docker-compose.yaml` file in project root folder. Then make sure you have Docker and Docker Compose or Docker Desktop installed and running on your machine. And now you are ready to do the following using your preferred command prompt:

- `docker compose up` - installs Postgres, Redis and Directus in separate containers and starts Directus instance on http://localhost:8055. To shut down Directus use Ctrl+C in running instance command prompt.
- `docker compose stop` - stops Postgres, Redis and Directus containers running in Docker when run in project root.
- `docker compose down` - removes Postgres, Redis and Directus containers from Docker when run in project root.
