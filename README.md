# ci-make-docker

ci-make-docker is a Docker image used for continuous integration where you want to utilize `make` to build Docker images. It is based of the `docker` images and additionally has `git` and `make` installed.


## Version matrix

Versions are based of the Docker version, as both `git` and `make` are versioned less often.

| Image   | Docker   | Git    | Make  |
| ------- | -------- | ------ | ----- |
| 18.09.5 | 18.09.5  | 2.20.1 | 4.2.1 |
