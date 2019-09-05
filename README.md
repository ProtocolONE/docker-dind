# About this repo

[![Docker Stars](https://img.shields.io/docker/stars/p1hub/dind.svg?style=flat)](https://hub.docker.com/r/p1hub/dind/) [![Docker Pulls](https://img.shields.io/docker/pulls/p1hub/dind.svg?style=flat)](https://hub.docker.com/r/p1hub/dind/)

This is a Dockerfile instructions to build a container image with **DIND** and some additional features  

* Docker-Compose
* CURL
* Make
* Git
* SSH Client
* GCC
* Bash

## Usage

```
docker run -it --rm --privileged --name dind -v /var/run/docker.sock:/var/run/docker.sock -v ${host_wd}:${container_wd} -w ${container_wd} p1hub/dind:latest
```  

## Versions

* tag: **latest** based on **docker:19**
* tag: **19** based on **docker:19**