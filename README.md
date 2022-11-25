# Project Skeleton PHP Symfony
Project skeleton dockerized with PHP 7.4 with framework symfony, Nginx, MySQL 8.0.26

I had a lot of difficulties to develop some things, with friends, version conflict among other problems (the famous "It works on my machine"), so with that in mind I created this repository on github containing a working environment in docker


Environment
- PHP v7.4 com Symfony v5.3
- Nginx Latest
- MySQL v8.0.26

To run the application on port 8080 on localhost(127.0.0.1), just run the command below in the folder where your project is

`docker-compose up -d`

To create entities, controllers, commands, etc, just run the command below in the folder where your project is

`docker-compose exec php74-service php bin/console make:entity/controller/command`
