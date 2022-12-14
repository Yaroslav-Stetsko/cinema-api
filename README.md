# DRF cinema-api

API for cinema project written using DRF

## Installation 

Install PostgresSQL and create db

```shell
git clone https://github.com/Yaroslav-Stetsko/cinema-api.git
cd cinema-api
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
set DB_HOST=<your db hostname>
set DB_NAME=<your db name>
set DB_USER=<your db username>
set DB_PASSWORD=<your db user password>
set SECRET_KEY=<your secret key>
python manage.py migrate
python manage.py runserver
```

## Run with docker

Docker has to be installed 

```shell
docker-compose build
docker-compose up
```

## Getting access

* create user -> http://127.0.0.1:8000/api/user/register/
* get access token -> http://127.0.0.1:8000/api/user/token/

## Features

* JWT authentication
* Managing Orders, Tickets, Cinema Halls & Movie Sessions directly from the website
* Adding Movies with Genres, Actors and Images
* Powerful admin panel for advanced managing
* Detailed documentation

