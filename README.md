# Django-auth-app
Django authorization app on Django 1.11


Copy the directories in you django project. If you dont have one, then run in cmd 

```django-admin startproject myproject```

Then copy dirs in "myproject" dir

* run ```python manage.py migrate```  
* run ```python manage.py runserver```


In myproject->settings add  'registration' to the INSTALLED APPS

add templates dir in TEMPLATES
...
'DIRS': ['templates/'],
...