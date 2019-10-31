# Traefik Drone

A Docker Compose configuration to run [Drone](https://drone.io/) behind a [Traefik](https://traefik.io/) reverse proxy.

## Usage

1. Clone this repository.
2. Copy `.env.example` to `.env` and modify the variables.
3. Register an OAuth application as described in the [Drone documentation](https://docs.drone.io/installation/providers/github/) and put the client id and secret in the `.env` file.
4. Run `docker-compose up -d`.
