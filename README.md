# Django authorization app
Django authorization app on Django 1.11
  
  
Create virtual environment using venv

Copy the directories in you django project. If you dont have one, then run in terminal

```django-admin startproject myproject```

Create a database, if you prefer something else than sqlite3 and write it in the local config
Then copy dirs in "myproject" directory

* run ```python manage.py migrate```  
* run ```python manage.py runserver```


In myproject->settings add  'registration' to the INSTALLED APPS

add templates dir in TEMPLATES.
...
'DIRS': ['templates/'],
...
