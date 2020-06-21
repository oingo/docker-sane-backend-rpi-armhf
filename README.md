## SANE Backend build environment (Raspberry Pi - ARMHF) Dockerfile


### Base Docker Image

* [balenalib/rpi-raspbian:jessie-20200429](https://hub.docker.com/r/balenalib/rpi-raspbian)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download : `docker pull oingo/sane-backend-rpi-armhf`


### Usage

    docker run -it -v <sane-backend-volume>:/root/project oingo/sane-backend-rpi-armhf /bin/bash
