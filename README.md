# About this Repo

[![Build Status](https://travis-ci.com/anaxexp/base-python.svg?branch=master)](https://travis-ci.com/anaxexp/base-python)
[![Docker Pulls](https://img.shields.io/docker/pulls/anaxexp/base-python.svg)](https://hub.docker.com/r/anaxexp/base-python)
[![Docker Stars](https://img.shields.io/docker/stars/anaxexp/base-python.svg)](https://hub.docker.com/r/anaxexp/base-python)
[![Docker Layers](https://images.microbadger.com/badges/image/anaxexp/base-python.svg)](https://microbadger.com/images/anaxexp/base-python)

This repository is a fork of https://github.com/docker-library/python with a few changes:

* We build only Alpine variants
* Base image changed to `anaxexp/alpine`
* Added debug variants compiled with `--with-pydebug` and non-strip bins

## Docker Images

* All images are based on Alpine Linux 3.8
* Base image: [anaxexp/alpine](https://github.com/anaxexp/alpine)
* [Travis CI builds](https://travis-ci.com/anaxexp/base-python) 
* [Docker Hub](https://hub.docker.com/r/anaxexp/base-python)

[_(Dockerfile 3.7)_]: https://github.com/anaxexp/base-python/tree/master/3.7/alpine3.8/Dockerfile.anaxexp
[_(Dockerfile 3.6)_]: https://github.com/anaxexp/base-python/tree/master/3.6/alpine3.8/Dockerfile.anaxexp
[_(Dockerfile 3.5)_]: https://github.com/anaxexp/base-python/tree/master/3.5/alpine3.8/Dockerfile.anaxexp
[_(Dockerfile 3.4)_]: https://github.com/anaxexp/base-python/tree/master/3.4/alpine3.8/Dockerfile.anaxexp
[_(Dockerfile 2.7)_]: https://github.com/anaxexp/base-python/tree/master/2.7/alpine3.8/Dockerfile.anaxexp

Supported tags and respective `Dockerfile` links:

* `3.7.0`, `3.7`, `3`, `latest` [_(Dockerfile 3.7)_]
* `3.6.6`, `3.6` [_(Dockerfile 3.6)_]
* `3.5.6`, `3.5` [_(Dockerfile 3.5)_]
* `3.4.9`, `3.4` [_(Dockerfile 3.4)_]
* `2.7.15`, `2.7`, `2` [_(Dockerfile 2.7)_]
* `3.7.0-debug`, `3.7-debug`, `3-debug` [_(Dockerfile 3.7)_]
* `3.6.6-debug`, `3.6-debug` [_(Dockerfile 3.6)_]
* `3.5.6-debug`, `3.5-debug` [_(Dockerfile 3.5)_]
* `3.4.9-debug`, `3.4-debug` [_(Dockerfile 3.4)_]
* `2.7.15-debug`, `2.7-debug`, `2-debug` [_(Dockerfile 2.7)_]

