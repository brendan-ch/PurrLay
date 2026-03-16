# PurrLay

Fork of the PurrNet Relay with deployment helpers. From the original:

- **PurrBalancer** registers the rooms and lets user know of all servers
- **PurrLay** is the relay and handles the actual game and connections

## Running locally

Install [Docker](https://docs.docker.com/manuals/), clone this repo, and run `docker compose up -d` to build and run the Compose project.

Verify the containers are running with Docker Desktop or by running `docker compose ps`.

Verify that the game connects by running `docker compose logs --follow`. It should say "Client connected to UDP" on a successful connection.
