# Directus docker setup using Postgres db and Redis cache

Clone the repo to your local machine and before installing change ADMIN_EMAIL and ADMIN_PASSWORD to your preferred values in the `docker-compose.yaml` file in project folder. Then make sure you have Docker and Docker Compose or Docker Desktop installed and running on your machine. Enter the project folder using your preferred command prompt and now you are ready to do the following:

- `docker compose up` - installs Postgres, Redis and Directus to Docker container named `directus-docker` if not already installed and starts Directus instance on http://localhost:8055. To shut down the container use Ctrl+C in running instance command prompt.
- `docker compose stop` - stops Postgres, Redis and Directus containers running in Docker when run in project root.
- `docker compose down` - removes Postgres, Redis and Directus containers from Docker when run in project root.
