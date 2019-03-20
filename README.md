# Ubuntu In a Docker with SSHD
![travis-ci Build Status](https://img.shields.io/travis/com/Luismcplopes/ubuntu-docker-sshd.svg?logo=travis)
![Docker Pulls](https://img.shields.io/docker/pulls/luismcplopes/ubuntu-docker-sshd.svg?style=popout?logo=docker)
[![last-commit](https://img.shields.io/github/last-commit/Luismcplopes/ubuntu-docker-sshd.svg?logo=github)](https://img.shields.io/github/last-commit/Luismcplopes/ubuntu-docker-sshd.svg?logo=github)
![docker build](https://img.shields.io/docker/build/luismcplopes/ubuntu-docker-sshd.svg?logo=docker)
[![license](https://img.shields.io/github/license/Luismcplopes/ubuntu-docker-sshd.svg?logo=github)](https://img.shields.io/github/license/Luismcplopes/ubuntu-docker-sshd.svg?logo=github)

## Ubuntu Dockerfile

This repository contains **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/_/ubuntu/) published to the public [Docker Hub Registry](https://hub.docker.com/r/luismcplopes/docker-ubuntu/).


### Base Docker Image

* [ubuntu:latest](https://hub.docker.com/r/luismcplopes/docker-ubuntu/)


### Installation

1. Install [Docker](https://docs.docker.com/install/).

2. Download [automated build](https://hub.docker.com/r/luismcplopes/docker-ubuntu/) from public [Docker Hub Registry](https://hub.docker.com/): `docker pull luismcplopes/docker-ubuntu`

   (alternatively, you can build an image from Dockerfile: `docker build -t="luismcplopes/ubuntu-docker-sshd" github.com/Luismcplopes/ubuntu-docker-sshd`)

[![Try in PWD](https://cdn.rawgit.com/play-with-docker/stacks/cff22438/assets/images/button.png)](http://play-with-docker.com)

### Usage

docker run -d --rm  -p 2222:2222 --name ubuntu-sshd luismcplopes/ubuntu-docker-sshd
