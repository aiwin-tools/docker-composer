docker-composer
===============

[Docker](https://www.docker.com/) container with [Composer](https://getcomposer.org/) and useful plugins for GitLab & Hipchat integrations

Usage
--------------

There is an assumption you have installed [docker-compose](https://docs.docker.com/compose/)

    docker-compose up


Build
--------------

Run `build.sh` script to build and push the image to default location

    aiwin/composer-base:latest

If you want to build and push the image to diferent location, define the following
variables before the execution of the script:

- REPOSITORY. Docker repository
- REGISTRY. Docker registry
- TAG. Tag or version
