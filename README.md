# Alpine Linux in Docker

[![Docker Automated build](https://img.shields.io/docker/automated/yobasystems/alpine.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/yobasystems/alpine/)
[![Docker Pulls](https://img.shields.io/docker/pulls/yobasystems/alpine.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/yobasystems/alpine/)
[![Docker Stars](https://img.shields.io/docker/stars/yobasystems/alpine.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/yobasystems/alpine/)

[![Alpine Version](https://img.shields.io/badge/Alpine%20version-v3.10.0-green.svg?style=for-the-badge)](https://alpinelinux.org/)


This Docker image [(yobasystems/alpine)](https://hub.docker.com/r/yobasystems/alpine/) is based on the minimal [Alpine Linux](https://alpinelinux.org/).

##### Alpine Version 3.10.0 (Released Jun 19, 2019)

This docker image is the base Alpine Linux. For more info on versions & support see [Releases](https://wiki.alpinelinux.org/wiki/Alpine_Linux:Releases)

----

## What is Alpine Linux?
Alpine Linux is a Linux distribution built around musl libc and BusyBox. The image is only 5 MB in size and has access to a package repository that is much more complete than other BusyBox based images. This makes Alpine Linux a great image base for utilities and even production applications. Read more about Alpine Linux here and you can see how their mantra fits in right at home with Docker images.

## Features

* Minimal size only, minimal layers
* Memory usage is minimal on a simple install.

## Architectures

* ```:amd64```, ```:x86_64``` - 64 bit Intel/AMD (x86_64/amd64)
* ```:arm64v8```, ```:aarch64``` - 64 bit ARM (ARMv8/aarch64)
* ```:arm32v7```, ```:armhf``` - 32 bit ARM (ARMv7/armhf)

#### PLEASE CHECK TAGS BELOW FOR SUPPORTED ARCHITECTURES, THE ABOVE IS A LIST OF EXPLANATION

## Tags

* ```:latest``` latest branch based (Automatic Architecture Selection)
* ```:master``` master branch usually inline with latest
* ```:3.9.3```, ```:3.9.3-arch``` version tag (Automatic Architecture Selection)
* ```:amd64```, ```:x86_64``` amd64 based on latest tag but amd64 architecture
* ```:aarch64```, ```:arm64v8``` Armv8 based on latest tag but arm64 architecture
* ```:armhf```, ```:arm32v7``` Armv7 based on latest tag but arm architecture

## Layers & Sizes

![Version](https://img.shields.io/badge/version-amd64-blue.svg?style=for-the-badge)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/yobasystems/alpine/amd64.svg?style=for-the-badge)
![MicroBadger Size (tag)](https://img.shields.io/microbadger/image-size/yobasystems/alpine/amd64.svg?style=for-the-badge)

![Version](https://img.shields.io/badge/version-aarch64-blue.svg?style=for-the-badge)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/yobasystems/alpine/aarch64.svg?style=for-the-badge)
![MicroBadger Size (tag)](https://img.shields.io/microbadger/image-size/yobasystems/alpine/aarch64.svg?style=for-the-badge)

![Version](https://img.shields.io/badge/version-armhf-blue.svg?style=for-the-badge)
![MicroBadger Layers (tag)](https://img.shields.io/microbadger/layers/yobasystems/alpine/armhf.svg?style=for-the-badge)
![MicroBadger Size (tag)](https://img.shields.io/microbadger/image-size/yobasystems/alpine/armhf.svg?style=for-the-badge)

## How to use this image
#### Usage
Use like you would any other base image:

```
FROM yobasystems/alpine
RUN apk add --no-cache mysql-client
ENTRYPOINT ["mysql"]
```
This example has a virtual image size of only 36.5MB. Compare that to our good friend Ubuntu:

```
FROM ubuntu:16.04
RUN apt-get update \
    && apt-get install -y --no-install-recommends mysql-client \
    && rm -rf /var/lib/apt/lists/*
ENTRYPOINT ["mysql"]
```
This yields us a virtual image size of about 184MB image.

## Source Repository

* [Gitlab - yobasystems/alpine](https://gitlab.com/yobasystems/alpine)

* [Bitbucket - yobasystems/alpine](https://bitbucket.org/yobasystems/alpine/)

* [Github - yobasystems/alpine](https://github.com/yobasystems/alpine)

## Links

* [Yoba Systems](https://www.yobasystems.co.uk/)

* [Dockerhub - yobasystems](https://hub.docker.com/u/yobasystems/)

* [Quay.io - yobasystems](https://quay.io/organization/yobasystems)
