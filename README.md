# AMP Docker Compose bootstrap
Ready to use `docker-compose.yml` file. For fast DevOps setting up the AMP project.

## AMP
* Apache with PHP 7.4 - `webdevops/php-apache:7.4`
* MySQL 8.0 - `mysql:8.0`
* Phpmyadmin - `phpmyadmin:5.0.2-apache`

## Config
Config should be specified in `./env` file with given properties.

_Note: by default Apache runs on port `:8000` and till now  (`v1.0.0`) doesn't support TLS_
## Run the containers
```
docker-compose up [-d]
```

## Contributing
Feel free to contribute by making Pull Request from `fork` on this repo.

***
_Shared on MIT License Copyright (c) 2020 Bartek Waliszko_

