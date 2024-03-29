# plausible

plausible is lightweight (< 1 KB) and privacy-friendly web analytics alternative to Google Analytics.

plausible [official docs](https://plausible.io/docs) and [github](https://github.com/plausible)

## Start

1. create env file `plausible-conf.env`. env files details see `.plausible-conf.env.sample`

```sh
touch plausible-conf.env
```

2. start container

```sh
docker-compose up -d
```

## Stop

```sh
docker-compose stop
```

## Uninstall

```sh
// after stop
docker-compose rm
```
