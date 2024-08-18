This is a readme markdown file for this tutorial project.
https://www.youtube.com/watch?v=F5OUT3ijk8M

## Steps for creating pipenv and django backend database:

- `mkdir [directory name]`
- `pipenv shell`
- `pipenv install django`
- `django-admin startproject backend`
- `cd backend & python3 manage.py startapp todo`
- `python3 manage.py migrate`

## Steps for setting up rest api

- `install djangorestframework and django-cors-headers`
-  add both to installed apps
-  add cors allowed origins
-  add cors middleware
-  create serializer
-  create views
-  add api url