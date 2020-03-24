# Folding@home Docker images

Docker images for [Folding@home](https://foldingathome.org/) with GPU support

[![Image bases on https://github.com/lukasheinrich/folding-at-home-docker](https://github.com/lukasheinrich/folding-at-home-docker)

## Build image

```
docker build -t mschnepf/folding-at-home:latest . -f Dockerfile
```

## Usage

```
docker run --rm mschnepf/folding-at-home:latest
```

