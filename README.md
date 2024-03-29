# container-portainer-agent

A Docker Compose container setup for the [Portainer Agent](https://github.com/portainer/agent).

## Table of contents

- [container-portainer-agent](#container-portainer-agent)
  - [Table of contents](#table-of-contents)
  - [Setup](#setup)

## Setup

0. Requirements

   - Docker
   - Docker Compose

1. Add environment variables

    Add the missing information for the environment variables:

    ```bash
    nano .env
    ```
    
    Mark the `.env` file so it's not tracked by git:

    ```bash
    git update-index --assume-unchanged .env
    ```

2. Start container

    ```bash
    docker-compose up -d
    ````

3. Stop container

    ```bash
    docker-compose down
    ```
