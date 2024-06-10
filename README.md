this API was build based on a tutorial, it uses flask_sqlalchemy and flask_marshmallow as well as sqlite and you can run it using [Postman](https://www.getpostman.com/postman) or just use CURL FTW! :smile:

# Running the apps

## Getting Your Environment Set Up

Run the following commands on a fresh clone of the repository to set up your virtualenv:
```bash
python3 -m venv .venv
source .venv/bin/activate
pip3 install -r requirements.txt
```

## Activating your Virtualenv

For any new terminal session, as long as you've already set up the `.venv` virtualenv, just run:

```bash
source .venv/bin/activate
pip3 install -r requirements.txt
```

You can then run either `app.py` or `crud.py`

## Deactivating your Virtualenv

Just run `deactivate` when you want to exit your virtualenv

### Running app.py

This will just display "Hello world...."

```bash
python3 app.py
```

### Running CRUD

This creates a SQLAlchemy local database and hosts a flask app with a REST API

```bash
python3 crud.py
```
