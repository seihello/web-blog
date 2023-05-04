```
python3 -m venv env
source env/bin/activate
pip install django
django-admin startproject blog
cd blog
python manage.py startapp webBlog
python manage.py runserver
```