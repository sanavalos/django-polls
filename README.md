# Polls

### Development steps
1- Create venv: python -m venv venv
2- Activate venv: .\venv\Scripts\activate
3- Install Django module: python -m pip install Django
4- Create template: django-admin startproject mysite django-project ("django-project" being the project folder's name)
5- Run server (test): python manage.py runserver
5- Generate basic directory structure for app: python manage.py startapp polls
6- Add polls to INSTALLED_APPS from settings: polls.apps.PollsConfig
7- Update TIME_ZONE variable from settings
8- Migrate changes: python manage.py migrate
9- Check for database tables: sqlite3 ./db.sqlite3
10- Create models/tables
11- Check SQL migrate: python manage.py sqlmigrate polls 0001
12- Check project problems: python manage.py check
13- Migrate model tables in database: python manage.py migrate