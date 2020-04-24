# Portainer Docker Application

Launch a standalone [Portainer](https://portainer.io) via [docker-app](https://github.com/docker/app) or [nimbusapp](https://github.com/admpresales/nimbusapp).

## Requirements

* Docker App [0.6.0](https://github.com/docker/app/tags/0.6.0)
* Docker Compose
* Nimbusapp (optional)

## Usage

### With Nimbusapp

```
nimbusapp jasoncorlett/portainer:latest up
```

### With Docker-app and Compose

```
docker-app jasoncorlett/portainer:latest render | docker-compose -p portainer up -d
```

