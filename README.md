# IoT Infrastructure Using Docker

Internet of Things Infrastructure

This repo has docker compose for IoT applications. The services includes keycloak for authentication, emqx for mqtt applications, caddy is the server routing data to the service through reverse proxying and postgres for storing data.

Steps to Run :

1. Install Docker.
2. Install Docker Compose.
3. create `.env` file in and copy `.env.example` content to it.
4. Change the environment variables with appropriate values.
5. Run `docker-compose pull` to download the docker images.
6. Run `docker-compose up` to run the container.
7. Run `docker-compose up -d` to run the container without attaching the logs.
8. Run `docker ps` to check if the program is running.
