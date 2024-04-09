first install venv `python -m venv venv`

then activate venv `venv\Scripts\activate`

then install Django inside venv `python -m pip install Django`

start project with `django-admin startproject mysite`

change into outer mysite directory `cd mysite`
start server `python manage.py runserver`

create polls app `python manage.py startapp polls`

add view by editting `views.py` in `mysite/polls/views.py`

add url path by creating and editting `urls.py` in `mysite/polls/urls.py`

point root URLConfig (`mysite/mysite/urls.py`) at `polls.urls` module

update timezone in `mysite/mysite/settings.py`

run `python manage.py migrate` from outer mysite
