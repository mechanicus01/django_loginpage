


## Setup

The first thing to do is to clone the repository:

```sh
$ git clone git@github.com:mechanicus01/django_loginpage.git
$ cd lushlyrics-webapp-django
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ python3 -mvenv django_webapp
$ source django_webapp/bin/activate
```

Then unzip the file `Lushlyrics-insecure.zip` and move it to the `django_webapp` folder.

```sh
$ unzip Lushlyrics-insecure.zip -d django_webapp

(django_webapp)$ cd Lushlyrics-insecure
```

Then install the dependencies:

```sh
(django_webapp)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv2`.

Once `pip` has finished downloading the dependencies:
```sh
(env)$ cd Lushlyrics-insecure
(env)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/`.
