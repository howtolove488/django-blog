# django-blog
Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design.
Django you want to make migrations

so let's make a new app: 
```bash
python manage.py startapp blog
```
migrations
```bash
python manage.py makemigrations
```
You can run a migrate, but there is one more check you can make:
```bash
python manage.py sqlmigrate blog 0001
```
createsuperuser
```bash
python manage.py createsuperuser
```
run server http://127.0.0.1:8000
```bash
python manage.py runserver
```
