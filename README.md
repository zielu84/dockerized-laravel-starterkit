# Dockerized Laravel starter kit


## Commands

Build images
> docker-compose --env-file .\app\.env build app

Start images in background
> docker-compose --env-file .\app\.env up -d

Composer usage
> docker-compose exec app composer install

Artisan usage
> docker-compose exec app php artisan key:generate

NPM usage
> docker-compose exec nodejs npm install