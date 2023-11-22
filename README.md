# MATLAB docker image

## Pull from dockerhub

```bash
docker pull marcantoine153/matlab_parpool:latest
```

## start docker container

```bash
docker compose up -d
```

By default MATLAB is running on web browser mode.
You can change running mode in [docker-compose.yml](docker-compose.yml) by change the option `command`.
More information can be found in [MATLAB dockerhub: How to use this image](https://hub.docker.com/r/mathworks/matlab)

## (optional) build docker image

```bash
docker compose build
```
