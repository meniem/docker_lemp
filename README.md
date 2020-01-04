# LEMP Stack using Docker Compose

This repo uses Docker-Compose to build a LEMP stack that uses Ubuntu 16.04, install nginx web server, MySQL DB, PHP-fpm and PHPMyAdmin.

# Prerequisites:
 - Docker.
 - Docker Compose.
 
 Installation:
 Use docker compose comamnd to build and run the containers.  commands.

  ```sh
docker-compose up -d
```
Once provisioned, check them using docker ps, and docker network ls:

```sh
netstat -plntu
docker ps
docker network ls
```
