# COURSE - Django framework na prática
> Visitor control system.
>
> <https://www.udemy.com/course/djangoframeworknapratica>
>
> [Certificate](https://ude.my/UC-f56f9e40-d3ac-41af-9443-154d733241e4/)

![Python Version](https://img.shields.io/badge/python-3.8.10-blue)
![SQLite Version](https://img.shields.io/badge/sqlite-3.x-blue)
![Django Version](https://img.shields.io/badge/django-3.2.10-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Installation

Create and activate a virtual environment in the root directory:

```sh  
python -m venv .venv
source .venv/bin/activate
```

Then install the requirements:

```sh  
pip install -r requirements.txt
```

Then run migrations to create the database/tables, run the server and create a superuser: 

```sh  
python manage.py migrate
python manage.py runserver
python manage.py createsuperuser
```