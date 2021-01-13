# minimum-docker-laravel

## Git Clone

```
$ git clone https://github.com/ucan-lab/minimum-docker-laravel.git
$ cd minimum-docker-laravel
```

## Create Laravel Project

```
$ docker-compose run composer create-project --prefer-dist laravel/laravel .

# Install laravel 6.x version
$ docker-compose run composer create-project --prefer-dist "laravel/laravel=6.*" .
```

## Laravel Server

```
$ docker-compose up -d app
```

http://localhost:8000

## Link

- https://github.com/ucan-lab/docker-laravel
- https://github.com/ucan-lab/docker-laravel-apache
