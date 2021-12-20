# Compose

Compose file: [httpd-php.yml](https://github.com/rodber/chevereto-free/blob/1.6/httpd-php.yml)

## Up

Run this command to spawn (start) Chevereto-Free.

```sh
docker-compose \
    -p chevereto-free \
    -f httpd-php.yml \
    up --abort-on-container-exit
```

[localhost:8810](http://localhost:8810)

## Stop

Run this command to stop Chevereto-Free.

```sh
docker-compose \
    -p chevereto-free \
    -f httpd-php.yml \
    stop
```

## Start

Run this command to start Chevereto-Free if stopped.

```sh
docker-compose \
    -p chevereto-free \
    -f httpd-php.yml \
    start
```

### Down (uninstall)

Run this command to down Chevereto-Free (stop containers, remove networks and volumes created by it).

```sh
docker-compose \
    -p chevereto-free \
    -f httpd-php.yml \
    down --volumes
```

## Logs

`todo`
