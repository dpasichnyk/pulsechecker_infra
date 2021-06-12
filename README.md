# Pulsechecker infra

Dockerized services for development.

## Requirements

Docker and docker-compose should be installed before you proceed.

## Project structure

 - `docker-compose.yml` defines services including monitoring.
 - `apps` folder contains sources for the services defined in `docker-compose.yml` with `volumes` specified.
 - `me` folder contains your custom scripts which are do not belong to any of the projects.

 ## Running
  - Normally `docker-compose up -d` should run make your services up and running.


