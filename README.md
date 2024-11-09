I copied the docker-compose.yml file from [SonarQube with PostgreSQL](https://github.com/SonarSource/docker-sonarqube/blob/master/example-compose-files/sq-with-postgres/docker-compose.yml) and made a few minor modifications for personal use.

# Prerequisites
- docker

# Installation
- `cp .env.example .env` - Feel free to change any default value.
- `docker-compose up -d` - Build and start the containers

Go to [http://localhost:9000](http://localhost:9000). If you changed the PORT, use that instead of 9000.

The default admin credentials are `admin/admin`.
