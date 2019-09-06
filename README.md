# Docker Image \w PHP, MySQL, Redis, Nginx

<a href="https://travis-ci.org/iSerter/docker-php-mysql-redis-nginx"><img src="https://travis-ci.org/iSerter/docker-php-mysql-redis-nginx.svg?branch=master" alt="Build Status"></a>

- PHP 7.3 
- MySQL 8.0
- Redis 5.0 
- Nginx 1.17
- Composer

### Run 
```
docker-compose up -d
```

### List & Confirm 
```
docker ps
```

### Compose
```
docker run --rm --interactive --tty --volume $PWD:/app composer install
```
See https://hub.docker.com/_/composer for more. 

### Stop
```
docker-compose stop
```

