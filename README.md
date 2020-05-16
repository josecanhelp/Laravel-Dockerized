# Laravel Dockerized
## A clean laravel application that can be run locally using Docker via docker-compose

## Configured Services
- PHP
- Nginx
- MySQL

### Get Started
#### Clone the application 

`git@github.com:josecanhelp/Laravel-Dockerized.git`

#### Copy .env file and modify to your needs

`cp .env.example .env`

#### Boot up the application using Docker

`docker-compose up -d`

#### Generate an application key

`docker-compose exec app php artisan key:generate`

#### Visit your app

`http://localhost`

#### Tear it all down

`docker-compose down`
