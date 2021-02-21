# Docker LAMPP with PHP 5.6 and MYSQL 5.6

Docker container for php 5.6 development. 🎉 

## How to use

1. Make sure [docker](https://docs.docker.com/get-started/#download-and-install-docker) and [docker-compose](https://docs.docker.com/compose/install/) is installed on your machine.
2. Clone this repository to your local machine with this command.
    ```bash
    https://github.com/wijaksanapanji/docker-lampp56.git
    ```
    then cd into the directory
    ```bash
    cd docker-lampp56
    ```
3. Run `docker-compose` to start the container.
    ```bash
    docker-compose up -d
    ```
4. Then you can open `apache` server at `http://localhost:8080` and `phpmyadmin` at `http://localhost:8081`
5. Place your `php` project at `public_html` directory, and you ready to go! 🚀 

## What is included

This docker environment included `php 5.6`, `mysql 5.6`, and `phpymadmin`. You can configure your php configuration in `php.ini` file located in `./php-apache/php.ini`.

## Some Environment Variable

```env
MYSQL_HOST = db
MYSQL_USER = root
MYSQL_PASSWORD = secret
```
You can change your `mysql` password on `docker-compose.yml` file.