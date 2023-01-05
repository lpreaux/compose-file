# Compose files

My compose files for running docker stacks

# Prerequisite

## Latest docker version

To run one these stack you need to have [Docker](https://www.docker.com/) install on the host system.

On desktop, the **Docker Desktop** app can be use. (app with GUI)
Use the [Official Doc](https://docs.docker.com/get-docker/) to install it.

For GUI-less use or on server, install **Docker Engine** using the [Official Doc](https://docs.docker.com/engine/install/)


# Usage

To use one of these compose file :

1. Download the file.
2. Move it in the desired folder on the host system.
3. To start the stack, either :

    - run `docker compose -f <name-of-the-compose-file.yml> up -d`

    or

    - rename the file to `docker-compose.yml` and run `docker compose up -d` (in the folder containing the file)