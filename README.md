# django_drf_jwt

## Installation
We're going to use pipenv as our packing tool. As this project already has a pipfile and a pipfile.lock, all you have to do is to spawn a shell and install all dependencies from the pipfile.
```bash
pipenv shell
pipenv install
```

After installating the dependencies, you will need to migrate your database.

```bash
python manage.py migrate
```
Now we're ready! Let's run the server and navigate to http://localhost:8000/api/token/.

```bash
python manage.py runserver
```

## Generating tokens

```bash
python manage.py createsuperuser
```
