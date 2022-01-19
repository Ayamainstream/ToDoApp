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
### First you can see login page where you should enter your login and password:

![image](https://user-images.githubusercontent.com/72498812/150188449-ab7a2649-2f22-44c9-a3c6-73d4426a2bef.png)

### If you haven't account you can create it in registration page:

![image](https://user-images.githubusercontent.com/72498812/150188653-2ed0fe26-38ae-45d8-bb6f-161ec1c1cfb3.png)

### Now if you sign in first you can see main page with your username and text to create new tasks:

![image](https://user-images.githubusercontent.com/72498812/150189052-3d372a3d-e13f-4be0-b8b0-25491f1dd34f.png)

### After clicking the button "Add a task" we redirect to task creation page. Here we can add any task what you want with description:

![image](https://user-images.githubusercontent.com/72498812/150189929-61dcee71-3868-495a-90c7-9bc525f34b35.png)

### Now here some tasks to show how work with it:

![image](https://user-images.githubusercontent.com/72498812/150190515-c2ead4a1-3c96-4410-b54b-39528eca3442.png)

### Here created some tasks so this task should be completed. To do this just need click to task and push complete:

![image](https://user-images.githubusercontent.com/72498812/150191141-1a09e86c-067f-43b5-9ba9-2d98b1857dd5.png)

![image](https://user-images.githubusercontent.com/72498812/150191149-3691012e-b82e-4e68-94dc-c5eab28bc51d.png)

### Also in this application tasks can be reordered with handle for needed order:

![image](https://user-images.githubusercontent.com/72498812/150191739-3951b939-f554-4753-b6fc-3e8ecf6bf889.png)

### And delete button for some unneded or completed tasks:

![image](https://user-images.githubusercontent.com/72498812/150191986-b7c18cfb-9bce-4ecd-ba71-997acf3d5599.png)

### For sign out you can click log out button on the right top of the page.

## License
[MIT](https://choosealicense.com/licenses/mit/)
