## Django Polls Application

(description)
Web application from the Django Tutorial project where users can vote on polls.


## Requirements

* Python 3.6 or newer
* Django 2.1.2 or newer
* Python add-on modules as in [requirements.txt](requirements.txt)
 
## Installation

* Clone django polls app

Open cmd and type
```
git clone https://github.com/gunnkrub/django-polls.git {your app directory name}
```

* Go to your django-polls directory on cmd.
```
cd {your app directory name}
```

* Create db.sqlite3.
```
py manage.py migrate
```

* Create .env file.
1. You need to create .env file in django-polls\mysite
2. open with text editor and put "DEBUG = True" in

* Create admin user on cmd.
```
py manage.py createsuperuser
```
Put your username, password, and email in.

## How to run

* type "py manage.py runserver" on cmd.
```
py manage.py runserver
```
* go to http://localhost:8000/ on your browser.



