# TODO REST API

REST API using flask and other packages

## How to - Setup for Linux

1. `virtualenv venv` to create the virtual env
2. `. venv/bin/activate` to active the virtualenv
3. `pip install -r requirements.txt` to install all dependencies on the virtual environment

## How to - Run locally

**The virtual environment must be active**

1. `export FLASK_API=app.py` need by flask
2. `flask run` to run the app in development mode
3. `curl http://localhost:5000/` to test a simple hello world endpoint

## How to - Run with docker compose

TODO write documentation