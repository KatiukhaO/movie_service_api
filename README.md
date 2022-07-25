# Movie cinema API

API service for cinema management.
Wrote with Django REST.


## Installing from GitHub

You should have or install PostgresSQL db and create db

```shell
git clone git@github.com:KatiukhaO/movie_service_api.git
python -m venv venv
venv/scripts/activate
pip install -r requirements.txt
set DB_HOST=<your db hostname>
set DB_NAME=<your db name>
set DB_USER=<your db username>
set DB_PASSWORD=<your db user password>
set SECRET_KEY=<your secret key>
python manage.py runserver
```


## Run with docker

Docker should be installed and run

```shell
docker-compose build
docker-compose up
```

## Access

- create user - /api/user/register/
- access token - /api/user/token/

## Features

* JWT authenticated
* Admin panel /admin/
* Documentation is located at /api/doc/swagger/
* Managing orders and tickets
* Creating movies with genres, actors
* Creating cinema halls
* Adding movie sessions
* Filtering movies and movie sessions
