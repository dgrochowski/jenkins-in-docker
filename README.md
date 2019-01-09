# Jenkins
Powered by [Docker](https://docs.docker.com/) with [Docker-compose](https://docs.docker.com/compose/) - [https://hub.docker.com/r/jenkins/jenkins](https://hub.docker.com/r/jenkins/jenkins)

- `docker-compose up --build -d`
- `http://localhost:7070`

## Upgrading to the latest version

- `docker-compose down`
- `docker pull jenkins/jenkins:lts`
- `docker-compose up --build -d`
