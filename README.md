# ga-django-python - part 1

This repository contains the source code for Part 1 of Introduction to Django 3.0 - Building, Authenticating, and Deploying. Read more at: (Add Link here).

In this article, we'll be learning the fundamentals of Django 2.0 and create a codesharing application that we'll be able to run on our local system. Below are the instructions to run the code.

## Requirements

1. Python3 and Git installed on your machine
2. Postgress Database
3. Auth0 Account
4. Heroku Account

## To run this:

1. Clone the repository: `git clone https://github.com/auth0-blog/ga-django-python.git`
2. Install all the packages using pip: `pip install -r "requirements.txt"`
3. Create Postgress DB with the name: `codeshare`
4. Run `python3 manage.py migrate` to make migrations
5. Run `python3 manage.py runserver` to start the server
6. Your browser should open automatically and show the application UI. If it doesn't start automatically, please open it manually and point it to http://localhost:8000
7. Run `python3 manage.py createsuperuser` to create a superuser in Django
