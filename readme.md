## Setup

The first thing to do is to clone the repository:

```sh
...\> git clone https://github.com/gocardless/sample-django-app.git
...\> cd sample-django-app
```

Create a virtual environment to install dependencies in and activate it:

```sh
...\> virtualenv2 --no-site-packages env
...\> source env/bin/activate
```

Then install the dependencies:

```sh
(env) ...\> pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv2`.

Once `pip` has finished downloading the dependencies:
```sh
(env) ...\> cd project
(env) ...\> python manage.py runserver
```
Then create a new app:
```sh
(env) ...\> django-admin startproject app 
```
