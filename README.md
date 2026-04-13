# Working-with_Django


## Create Project

```
❯ django-admin startproject app_base main_project
```

```
main_project/
├── app_base
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── manage.py

2 directories, 6 files
```

```
❯ cd main_project/
❯ python manage.py  migrate
❯ python manage.py  createsuperuser
❯ python manage.py  runserver
```


## Add another Apps

```
❯ python manage.py  startapp app_crud
❯ python manage.py  startapp app_view
❯ python manage.py  startapp app_test
```

```
❯ tree -d .
.
├── app_base
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── app_crud
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── app_test
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── app_view
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
└── manage.py

8 directories, 27 files
```

