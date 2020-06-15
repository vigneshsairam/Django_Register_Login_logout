# Django_Register_Login_logout

create app in django using command: python manage.py startapp
add command to your Installed_apps List in settings.py folder: 'register.apps.RegisterConfig'

install crispy package in django using command: pip install django-crispy-forms
add command to your settings.py in project folder: CRISPY_TEMPLATE_PACK="bootstrap4"

add command below to your urlpatterns in urls.py in project folder:
path("register/", v.register, name="register"),
path('', include("django.contrib.auth.urls"))


                                                           Thank You☺
