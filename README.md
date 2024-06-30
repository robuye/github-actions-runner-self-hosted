## Github Actions self-hosted runners with build-essentials

Github Actions runner image based on Ubuntu 22.04 with build-essentials preinstalled.

https://hub.docker.com/r/robuye/github-actions-runner-self-hosted

Official images lack build-essentials, details and reasoning are here:

https://github.com/actions/actions-runner-controller/issues/3000

https://github.com/actions/actions-runner-controller/pull/2050

## Building locally

```
docker build - < Dockerfile.ubuntu-22.04
```
