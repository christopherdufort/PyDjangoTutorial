# PyDjangoTutorial
A simple web app created in Python + Django following djangoproject.com tutorial

## Built using:
* Python 3.7.0
* Django 2.1.2
* Sqlite 3.25.1

### To run server:
1. `cd mysite`
2. `python manage.py runserver`

#### To access the interactive shell
* `python manage.py shell`

###### Code to get DB up and running
* Make changes to models in polls/models.py
* run `python manage.py makemigrations polls`
* run `python manage.py migrate`