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

## Github Action

[hey.yml](.github/workflows/hey.yml) - sample config to run hey in GitHub Actions CI/CD workflow. It runs `hey` against https://1.1.1.1 and reports results in a build log

### Github Action Quickstart:

1. Fork this repo
2. [Enable actions](https://docs-github-com.translate.goog/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository)
3. Commit any changes in your repo
4. Check `Actions` tab
