# To-do-List-App
a little app to manage your daily tasks

## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/EmmanuelHillary/To-do-List-App.git
$ cd To-do-List-App
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ py -3 -m venv env
$ env\Scripts\activate
```
Or use the virtual env from the repo 

```sh
$ tmenv\Scripts\activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment 

Once `pip` has finished downloading the dependencies:

```sh
(env)$ cd django-project
```
make make migrations and push the migrations

```sh
(env)$ python manage.py makemigrations
(env)$ python manage.py migrate

```

create an admin user

```sh
(env)$ python manage.py createsuperuser
```

then run the server

```sh
(env)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/`.

![Alt text](https://github.com/EmmanuelHillary/To-do-List-App/blob/main/images/Homepage.png?raw=true "Homepage")
