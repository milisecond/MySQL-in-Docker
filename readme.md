<img src="icon.png" align="right" />

![Awesome](https://img.shields.io/badge/Docker-2CA5E0?style=flat=docker&logoColor=white)
![Awesome](https://img.shields.io/badge/MySQL-005C84?style=flat&logo=mysql&logoColor=white)

# MySQL in Docker

## Pre-installation
1. Install docker
2. Install docker-compose

## Installation
1. From this root of project "./" execute command `docker-compose up`
2. Then, run this command `docker exec -it mysql_container bash` to log in your container bash.
4. or just run this command `docker -it mysql_container mysql -uroot -p111 -P3307` to log in your mysql instance
5. Done forget to adjust your .env file

