Psysh
=====
[![Docker Automated build](https://img.shields.io/docker/automated/connrs/psysh.svg?style=flat-square)](https://hub.docker.com/r/connrs/psysh/)
[![Docker Build Status](https://img.shields.io/docker/build/connrs/psysh.svg?style=flat-square)](https://hub.docker.com/r/connrs/psysh/)

Docker image [psy/psysh](https://github.com/bobthecow/psysh)

Usage
-------

``` bash
$ docker run -v $(pwd):/app -it connrs/psysh
```

Docker Compose
-------

Example docker-compose.yml file
```
version: '3.2'

services:
  interactive:
    volumes:
      - ./:/app
    image: connrs/psysh:latest
```

Then run:
``` bash
$ docker-compose run interactive
```
