# ToDo app with authentication in Django
It is ToDo application with authentication using Django Web Framework. As database used database Postgresql.

## Installation
Install Django framework:
```bash
pip install Django
```
Create an empty database in your PostgreSQL. Create a database alias for PostgreSQL in your Django settings file:
```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'DATABASE_NAME',
        'USER': 'USERNAME',
        'PASSWORD': 'PASSWORD',
        'HOST': 'localhost'
    }
}
```
Then you can just migrate all models by commands like:
```bash
python manage.py makemigrations
```
```
python manage.py migrate
```
## Usage
This project located on your device, so to use this application you need to follow the link on your terminal or just write http://127.0.0.1:8000/

## Examples
First you can see login page where you should enter your login and password:
