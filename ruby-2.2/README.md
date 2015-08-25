# ansible-debian-jessie/ruby:2.2
This repository contains the Dockerfile for the `ansible-debian-jessie/ruby` image.

## Base Docker Image
- [ansible-debian-jessie/base](https://github.com/josemrb/docker-ansible-debian-jessie)

## Installation
### Install Docker
See Docker [documentation](https://docs.docker.com/installation/)

### Clone repository
```sh
$ git clone git@github.com:josemrb/docker-ansible-debian-jessie.git
$ cd docker-ansible-debian-jessie/ruby-2.2
```

### Build Image
```sh
$ docker build -t ansible-debian-jessie/ruby:2.2 .
```

### Usage
```sh
$ docker run -i -t --rm ansible-debian-jessie/ruby:2.2
```
