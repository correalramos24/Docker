# Dockerfiles

- [Dockerfiles](#dockerfiles)
  - [Dockerfiles commands](#dockerfiles-commands)
  - [Image generation (docker build)](#image-generation-docker-build)


Boilerplate to generate docker images, consists in a sequence of *commands* that adds layers to a parent image.

> Is a good practice to use a pre-designed image from a registry (docker hub for example).

## Dockerfiles commands

* WORKDIR path
* COPY host_src container_target
* RUN cmd

* CMD
* ENTRYPOINT 

## Image generation (docker build)


For add a tag to the image, you can use `docker build -t tag .`. Otherwise ...
