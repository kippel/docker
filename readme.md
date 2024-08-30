# docker

## Django

### movies un

[![Django Badge](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=fff&style=for-the-badge)](https://www.djangoproject.com/)
[![SQLite Badge](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=fff&style=for-the-badge)](https://www.sqlite.org/)
[![Docker Badge](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=Docker&logoColor=white)](https://www.docker.com/)
[![Docker-compose](https://img.shields.io/badge/Docker-compose-2496ED.svg?style=for-the-badge&logo=Docker&logoColor=white)](https://docs.docker.com/compose/)

$ docker compose build

$ docker compose run --rm web sh -c "django-admin startproject core ."

$ docker compose up

$ docker compose run --rm web sh -c "python manage.py startapp red"

$ docker compose up

### movies dos

[![Django Badge](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=fff&style=for-the-badge)](https://www.djangoproject.com/)
[![SQLAlchemy Badge](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=fff&style=for-the-badge)](https://www.sqlalchemy.org/)
[![Docker Badge](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=Docker&logoColor=white)](https://www.docker.com/)
[![Docker-compose](https://img.shields.io/badge/Docker-compose-2496ED.svg?style=for-the-badge&logo=Docker&logoColor=white)](https://docs.docker.com/compose/)

https://img.shields.io/badge/pgAdmin-4.21-blue

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
