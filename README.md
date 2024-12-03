# docker-quetre

`docker pull ghcr.io/shindouj/quetre:latest`

A [Quetre](https://github.com/zyachel/quetre) image, forked from [PussTheCat](https://github.com/PussTheCat-org/docker-quetre-quay).
Used for the [jeikobu.net](https://quetre.jeikobu.net) instance. The main difference is creating images only when an actual change in code has occured.

## Usage:

- Download (or copy the content of) the `docker-compose.yml` to any folder you want
- (Optional) Customize the environment variable with the settings you want to apply
- `docker-compose up -d`
