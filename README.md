# storefront-django-backend

django-tutorial

1. Create project using the command "django-admin startproject storefront ."
   This will create the following files

-   __init__.py: Defines directory as a package
-   settings.py: Define out app settings
-   urls.py: Define URLs of our app
-   manage.py: Wrapper around manage.py (takes in the settings of this project into account)

2. Use command "python3 manage.py runserver 5000" to run the project
3. Create a new app for your django project using the command "python3 manage.py startapp playground" which will create a dir called playground with the following files

-   migrations: Folder for generating Database tables
-   admin.py: Defines how the admin interface for this app would look like
-   apps.py: Configuration for the App
-   models.py: Defines Model Classes for the App
-   tests.py: Contains unit tests
-   views.py: Contains request handlers (think of it like the controller methods, which takes in requests and returns response)

Once we create a new app, we need to configure this in the settings of the project

4. Create a urls.py (name can be anything) file in the playground to map the routes to the view methods. This should contain urlpatterns which will be an array of URLPattern objects. This file
