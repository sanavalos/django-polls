# Polls

### Development steps

1. Create venv: ```python -m venv venv```
2. Activate venv: ```.\venv\Scripts\activate```
3. Install Django module: ```python -m pip install Django```
4. Create template: ```django-admin startproject mysite django-project``` ("django-project" being the project folder's name)
5. Run server (test): ```python manage.py runserver```
6. Generate basic directory structure for app: ```python manage.py startapp polls```
7. Add polls to INSTALLED_APPS from settings: polls.apps.PollsConfig
8. Update TIME_ZONE variable from settings
9. Migrate changes: ```python manage.py migrate```
10. Check for database tables: ```sqlite3 ./db.sqlite3```
11. Create models/tables
12. Check SQL migrate: ```python manage.py sqlmigrate polls 0001```
13. Check project problems: ```python manage.py check```
14. Migrate model tables in database: ```python manage.py migrate```
15. Add models to admin panel
16. Create views
17. Create urls
18. Create templates and polls directory with htmls
19. Add templates to urls
20. Use generic views
21. Create test file and functions