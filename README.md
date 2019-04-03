# Jenkins
Powered by [Docker](https://docs.docker.com/) with [Docker-compose](https://docs.docker.com/compose/) - [https://hub.docker.com/r/jenkins/jenkins](https://hub.docker.com/r/jenkins/jenkins)

## How to use

- prepare `.env` file (`.env.dist` is an example file)
- start container `docker-compose up --build -d`
- visit `http://localhost:8080`

## Log into container

- `docker-compose exec jenkins bash`

## Upgrading to the latest version

- `docker-compose down`
- `docker pull jenkins/jenkins:lts`
- `docker-compose up --build -d`
