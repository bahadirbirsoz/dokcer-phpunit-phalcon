# docker-phpunit-phalcon-boilerplate

## Get Started


* You need to create your .env file. example.env is provided. Just rename and change. 

* nginx is configured to listen port 80. You can change it from docker-compose.yml

To run
```
docker-compose up --build
```

###Complete Phalcon Development Environment

FROM php:7.4-fpm
- PHP 7.4
- Phalcon 4.1.0
- PHP Zephir Parser 1.3.6
- Zephir 0.12.20
- Composer
- PhpUnit
- Xdebug
- Nginx
- Mysql

