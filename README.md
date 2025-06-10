# `hey` samples

## Tool

[rakyll/hey: HTTP load generator, ApacheBench (ab) replacement](https://github.com/rakyll/hey)

> hey is a tiny program that sends some load to a web application.

## samples

* [hey against 1.1.1.1](docker-compose-1.1.1.1.yml)
```
docker compose up -f docker-compose-1.1.1.1.yml --abort-on-container-exit
```

* [hey against python webserver](docker-compose-python.yml)
```
docker compose up -f docker-compose-python.yml --abort-on-container-exit
```

* [hey against nginx](docker-compose-nginx80.yml)
```
docker compose up -f docker-compose-nginx80.yml --abort-on-container-exit
```
