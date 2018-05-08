# SilverStripe Docker

## Motivation
I wanted a complete setup of a SilverStripe LAMP stack (normal LAMP with Apache configs for the document root and SilverStripe specific config), but couldn't find a simple solution. This should get you up and running quickly to develop a SilverStripe application (and probably other frameworks too - but not tested).
Wrapping `Make` around docker-compose commands makes it easier to interact with containers.

## Requirements
- [Docker for Mac](https://www.docker.com/docker-mac) or [Docker for Windows](https://www.docker.com/docker-windows)
- [Make](https://www.gnu.org/software/make)

## How to setup
- Copy `docker-compose.yml`, `Dockerfile`, and `Makefile` into your project.
- Run `make init` in your project root.

You can run `make clean up` to reload the containers after changing environment variables.
