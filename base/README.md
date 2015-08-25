# ansible-debian-jessie/base
This repository contains the Dockerfile for the `ansible-debian-jessie/base` image.

## Base Docker Image
- [debian:jessie](https://github.com/tianon/docker-brew-debian)

## Installation
### Install Docker
See Docker [documentation](https://docs.docker.com/installation/)

### Clone repository
```sh
$ git clone git@github.com:josemrb/docker-ansible-debian-jessie.git
$ cd docker-ansible-debian-jessie/base
```

### Build Image
```sh
$ docker build -t ansible-debian-jessie/base .
```

### Usage
```sh
$ docker run -i -t --rm ansible-debian-jessie/base
```
