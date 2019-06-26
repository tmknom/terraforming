# terraforming

[![CircleCI](https://circleci.com/gh/tmknom/terraforming.svg?style=svg)](https://circleci.com/gh/tmknom/terraforming)
[![Docker Build Status](https://img.shields.io/docker/cloud/build/tmknom/terraforming.svg)](https://hub.docker.com/r/tmknom/terraforming/builds/)
[![Docker Automated build](https://img.shields.io/docker/cloud/automated/tmknom/terraforming.svg)](https://hub.docker.com/r/tmknom/terraforming/)
[![MicroBadger Size](https://img.shields.io/microbadger/image-size/tmknom/terraforming.svg)](https://microbadger.com/images/tmknom/terraforming)
[![MicroBadger Layers](https://img.shields.io/microbadger/layers/tmknom/terraforming.svg)](https://microbadger.com/images/tmknom/terraforming)
[![License](https://img.shields.io/github/license/tmknom/terraforming.svg)](https://opensource.org/licenses/Apache-2.0)

Dockerfile template.

## Requirements

- [Docker](https://www.docker.com/)

## Usage

```sh
curl -fsSL https://raw.githubusercontent.com/tmknom/terraforming/master/install | sh -s example
cd example
```

## Makefile targets

```text
build                          Build docker image
format                         Format code
help                           Show help
install                        Install requirements
lint                           Lint code
```

## Development

### Installation

```shell
git clone git@github.com:tmknom/terraforming.git
cd terraforming
make install
```

### Deployment

Automatically deployed by "[DockerHub Automated Build](https://docs.docker.com/docker-hub/builds/)" after merge.

### Deployment Pipeline

1. GitHub - Version Control System
   - <https://github.com/tmknom/terraforming>
2. CircleCI - Continuous Integration
   - <https://circleci.com/gh/tmknom/terraforming>
3. Docker Hub - Docker Registry
   - <https://hub.docker.com/r/tmknom/terraforming>
4. MicroBadger - Docker Inspection
   - <https://microbadger.com/images/tmknom/terraforming>

## License

Apache 2 Licensed. See LICENSE for full details.
