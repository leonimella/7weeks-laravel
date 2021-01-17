# Larabloug

A Laravel implementation of the Bloug.

## Installation

### First time

1) Copy the `.env.example` file to `.env`

2) Open `.env` change the database credentials accordingly with yours

Now we must run `docker-compose` to setup the application

3) Installing packages with composer
```shell
docker-compose run --rm app composer install
```

5) Generate app key
```shell
docker-compose run --rm app php artisan key:generate
```

6) Add permission to `storage` folder
```shell
docker-compose run --rm app chmod -R 777 /var/www/larabloug/storage
```

### Running the app
Just run the `docker-compose`command to get your app up and running:
```shell
docker-compose up -d
```

Enjoy! 🚀
