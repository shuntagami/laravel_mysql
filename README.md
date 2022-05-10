# Setup

```bash
$ cp .env.example .env
$ docker-compose build admin
$ docker-compose run --rm admin composer install
$ docker-compose run --rm admin php artisan key:generate
$ docker-compose up admin
```
