# CharacterCreatorDnD
Service for helping with character creation in DnD 5e

## Setup
* You will need all the necessary packages for developing in `python` and the packages for `postgres` appropriate for your system.
* Create a virtual environment for Python using `virutalenv env` in the root of the project.
* Activate the virtual environment using `source env/activate/bin`. Install the necessary requirements using `pip install -r requirements.txt`.
* A postgres database needs to be setup for the prject. Instructions can be found [here](https://www.digitalocean.com/community/tutorials/how-to-use-postgresql-with-your-django-application-on-ubuntu-14-04).
* Create a file in the CharacterCreator folder called `settings_secret.py` and fill in the strings with the appropriate data for your setup:
```
DATABASE_NAME = 'nameofdatabase'
DATABASE_USERNAME = 'yourusername'
DATABASE_PASSWORD = 'yourpassword'
```

## Development
* In the root folder, use `python manage.py runserver` to get the server running on localhost:8000 . If you need it to run on another port, simply run e.g. `python manage.py runserver 1234` to get it to run on localhost:1234 .
