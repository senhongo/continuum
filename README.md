# Continuum

Docker containers for a local dev environment.

## Run commands

TEMP run commands until Dockerfile and docker-compose / kubernetes is ready

## postgres

Runs latest version of postgres and maintains the data in the `continuum_postgres-data` volume

To start: `docker-compose up -d`

To stop and remove: `docker-compose down`

To check volumes: `docker volume ls`

To remove volume: `docker volume rm continuum_postgres-data`

## pihole
