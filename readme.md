# docker

## Django

### movies un


$ docker compose build

$ docker compose run --rm web sh -c "django-admin startproject core ."

$ docker compose up

$ docker compose run --rm web sh -c "python manage.py startapp red"

$ docker compose up

### movies dos

$ docker compose build

$ docker compose run --rm web sh -c "django-admin startproject core ."

$ docker compose up

$ docker compose run --rm web sh -c "python manage.py startapp movies"

$ docker compose up

$ docker compose run --rm web sh -c "python manage.py createsuperuser"

```
Username (leave blank to use 'web'): kippel
Email address: <user@gmail.com>
Password:
Password (again):
Superuser created successfully.
``` 
