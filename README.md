# Alpine Linux Container Image

[![Docker Automated build](https://img.shields.io/docker/automated/yobasystems/alpine.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/yobasystems/alpine/)
[![Docker Pulls](https://img.shields.io/docker/pulls/yobasystems/alpine.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/yobasystems/alpine/)
[![Docker Stars](https://img.shields.io/docker/stars/yobasystems/alpine.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/yobasystems/alpine/)

[![Alpine Version](https://img.shields.io/badge/Alpine%20version-v3.22.0-green.svg?style=for-the-badge&logo=alpine-linux)](https://alpinelinux.org/)


This Container image [(yobasystems/alpine)](https://hub.docker.com/r/yobasystems/alpine/) is based on the minimal [Alpine Linux](https://alpinelinux.org/).

### Alpine Version 3.22.0 (Released 2025-05-30)
### Alpine Version 3.21.3 (Released 2025-02-13)
### Alpine Version 3.20.6 (Released 2025-02-13)
### Alpine Version 3.19.7 (Released 2025-02-13)
### Alpine Version 3.18.12 (Released 2025-02-13)




This Container image is the base Alpine Linux. For more info on versions & support see [Releases](https://wiki.alpinelinux.org/wiki/Alpine_Linux:Releases)

----


## Table of Contents

- [What is Alpine Linux?](#what-is-alpine-linux)
- [Features](#features)
- [Architectures](#architectures)
- [Tags](#tags)
- [Layers & Sizes](#layers-sizes)
- [How to use this image](#how-to-use-this-image)
- [Image contents & Vulnerability analysis](#image-contents-vulnerability-analysis)
- [Source Repositories](#source-repositories)
- [Container Registries](#container-registries)
- [Links](#links)


## 🏔️ What is Alpine Linux?
Alpine Linux is a Linux distribution built around musl libc and BusyBox. The image is only 5 MB in size and has access to a package repository that is much more complete than other BusyBox based images. This makes Alpine Linux a great image base for utilities and even production applications. Read more about Alpine Linux here and you can see how their mantra fits in right at home with Container images.

## ✨ Features

* Minimal size only, minimal layers
* Memory usage is minimal on a simple install.

## 🏗️ Architectures

* ```:amd64```, ```:x86_64``` - 64 bit Intel/AMD (x86_64/amd64)
* ```:arm64v8```, ```:aarch64``` - 64 bit ARM (ARMv8/aarch64)
* ```:arm32v7```, ```:armhf``` - 32 bit ARM (ARMv7/armhf)

#### 📝 PLEASE CHECK TAGS BELOW FOR SUPPORTED ARCHITECTURES, THE ABOVE IS A LIST OF EXPLANATION

## 🏷️ Tags

* ```:latest``` latest branch based on main(Automatic Architecture Selection)
* ```:main``` main branch usually inline with :latest
* ```:x.y.z```, ```:x.y.z-arch``` version tag (Automatic Architecture Selection)
* ```:amd64```, ```:x86_64``` amd64 based on latest tag but amd64 architecture
* ```:aarch64```, ```:arm64v8``` Armv8 based on latest tag but arm64 architecture
* ```:armhf```, ```:arm32v7``` Armv7 based on latest tag but arm architecture

## 📏 Layers & Sizes

![Version](https://img.shields.io/badge/version-amd64-blue.svg?style=for-the-badge)
![Docker Image Version (tag)](https://img.shields.io/docker/v/yobasystems/alpine/amd64.svg?style=for-the-badge)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/yobasystems/alpine/amd64.svg?style=for-the-badge)

![Version](https://img.shields.io/badge/version-aarch64-blue.svg?style=for-the-badge)
![Docker Image Version (tag)](https://img.shields.io/docker/v/yobasystems/alpine/aarch64.svg?style=for-the-badge)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/yobasystems/alpine/aarch64.svg?style=for-the-badge)

![Version](https://img.shields.io/badge/version-armhf-blue.svg?style=for-the-badge)
![Docker Image Version (tag)](https://img.shields.io/docker/v/yobasystems/alpine/armhf.svg?style=for-the-badge)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/yobasystems/alpine/armhf.svg?style=for-the-badge)

## 🚀 How to use this image
#### Usage
Use like you would any other base image:

```
FROM yobasystems/alpine
RUN apk add --no-cache mysql-client
ENTRYPOINT ["mysql"]
```
This example has a base image size of only 6MB. Compare that to our good friend Ubuntu:

```
FROM ubuntu
RUN apt-get update \
    && apt-get install -y --no-install-recommends mysql-client \
    && rm -rf /var/lib/apt/lists/*
ENTRYPOINT ["mysql"]
```
This yields us a base image size of about 74MB image.

## 🔍 Image contents & Vulnerability analysis

| PACKAGE NAME          | PACKAGE VERSION | VULNERABILITIES |
|-----------------------|-----------------|-----------------|


## 📚 Source Repositories

* [Github - yobasystems/alpine](https://github.com/yobasystems/alpine)
* [Gitlab - yobasystems/alpine](https://gitlab.com/yobasystems/alpine)
* [Bitbucket - yobasystems/alpine](https://bitbucket.org/yobasystems/alpine/)


## 🐳 Container Registries

* [Dockerhub - yobasystems/alpine](https://hub.docker.com/r/yobasystems/alpine/)
* [Quay.io - yobasystems/alpine](https://quay.io/repository/yobasystems/alpine)
* [GHCR - yobasystems/alpine](https://ghcr.io/yobasystems/alpine)


## 🔗 Links

* [Yoba Systems](https://www.yobasystems.co.uk/)
* [Github - Yoba Systems](https://github.com/yobasystems/)
* [Dockerhub - Yoba Systems](https://hub.docker.com/u/yobasystems/)
* [GHCR - Yoba Systems](https://ghcr.io/yobasystems)
* [Quay.io - Yoba Systems](https://quay.io/organization/yobasystems)
* [Maintainer - Dominic Taylor](https://github.com/dominictayloruk)
