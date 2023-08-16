# Roasters Backend
Where the beans dry and become flavorful ☕️

## Getting started
### Install python3 & pip3
- Install pyenv: `brew install pyenv`
- cd into directory of the application
- Install latest python `pyenv install 3.11`
- Set python version in directory `pyenv local 3.11`

_Note if you have python3 installed, it might be useful to create some aliases such as the following_:
- `alias python=/usr/bin/python3`
- `alias pip=/usr/bin/pip3`

### Manage python packages
- `pipreqs` is great for [python package management](https://betterdatascience.com/python-pipreqs/)
- `pip install pipreqs`
- To save packages installed, run `pipreqs` after pip installations

### Install Postgres
- Follow any of the ways listed [here](https://www.postgresql.org/download/macosx/)
- Install the psycopg2 package using `pip install psycopg2`

- `brew install postgresql@15`

### Run the server
- `python manage.py runserver`

### Create tables in postgresSQL
- Create a model file
- Add model to `admin.py`
- Create the migrations: `python manage.py makemigrations`
- Run the migrations: `python manage.py migrate`

#### Most of this was using this article
- https://stackpython.medium.com/how-to-start-django-project-with-a-database-postgresql-aaa1d74659d8
- I can't get pgAdmin to work anymore and I can't log in to the postgres database at the moment, I'll need to verify these tables were made later
