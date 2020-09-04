# Lead Manager React Django

## Installation Instructions

Clone the repo

```bash
$ git clone https://github.com/KatherineMichel/lead_manager_react_django/
```

`cd` into the directory

```bash
$ cd lead_manager_react_django
```

Create a virtualenv

```bash
$ pipenv shell
```

Install the Python dependencies

```bash
$ pipenv install
```

Install the JavaScript dependencies

```bash
$ npm install
```

Make migrations and migrate

```bash
$ cd leadmanager
$ python manage.py makemigrations leads
$ python manage.py migrate
```

Run Python dev server

```bash
$ python manage.py runserver
```

Compile JavaScript into `main.js` and run JavaScript dev server

```bash
$ cd .. # cd into root
$ npm run dev
```

Go to: http://127.0.0.1:8000/
