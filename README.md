# Project url-word-counter

Counts words from scraped URL in Flask

## Quick Start

### First Steps

```sh
$ pyvenv-3.6 env
$ source env/bin/activate
$ pip install -r requirements.txt
```

### Set up Migrations

```sh
$ python manage.py db init
$ python manage.py db migrate
$ python manage.py db upgrade
```

### Run

Run each in a different terminal window...

```sh
# redis
$ redis server

# worker process
$ python worker.py

# the app
$ python app.py
```

## Credits

Based on great tutorial at https://realpython.com/flask-by-example-part-1-project-setup/
