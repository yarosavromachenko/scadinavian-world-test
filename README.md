# ScandinavianWorld
A Symfony project created on December 12, 2025, 5:30 pm.

# 🐳 Project Docker Setup

This project includes a fully containerized Docker environment for easy local development.

## 📦 Requirements

- [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/) installed

Database default connection: (can be edited in `.env`)
- DB_USER: `root`
- DB_PASSWORD: `root`
- DB_HOST: `db`
- DB_PORT: `3306`
- DB_NAME: `scandinavian_world`,

## 🔧 Quick Start
Edit .env if needed
run command `docker-compose up --build`

## 🛠 Common Docker Commands
| Purpose                                                                                                                                            | Command                                     |
|----------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------|
| [Builds, (re)creates, starts, and attaches to containers for a service](https://docs.docker.com/reference/cli/docker/compose/up/)                  | `docker compose up [OPTIONS] [SERVICE...]`  |
| [Stops containers and removes containers, networks, volumes, and images created by up](https://docs.docker.com/reference/cli/docker/compose/down/) | `docker compose down [OPTIONS] [SERVICES]`  |
| [View output from containers](https://docs.docker.com/reference/cli/docker/compose/logs/)                                                          | `docker compose logs [OPTIONS] [SERVICE...]`|
💡 Docker [documentation](https://docs.docker.com/reference/cli/docker/compose/) for other commands

## 🌐 Configurations and accessibility
After docker build project should be accessible by link [http://127.0.0.1:8000].