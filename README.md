# django-basics
Check install packages: pip freeze
Crete virtual environment: python -m venv env
Activate virtual environment: source env/scripts/activate
Deactivate virtual environment: deactivate
Install django: pip install django
Run project: python manage.py runserver
Create django project: django-admin startproject myproject ==> (here myproject is project name)
Create app: python manage.py startapp students ==> (here students is app name)
After creating static folder run command: python manage.py collectstatic
After creating model - run migration command: python manage.py makemigrations, python manage.py migrate
Create super user: winpty python manage.py createsuperuser  ==> winpty is for bash


Packages:
pillow for images
pip install pillow



asgi - asynchromous server gateway interface