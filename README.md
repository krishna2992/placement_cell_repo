Student Placement Cell is Placement cell Website for Colleges.

To run locally, do the usual:

Create a Python 3.8+ virtualenv and activate it

Install dependencies:

Install dependencies from requirments.txt

Create a superuser/admin for Your Site

Run Below Command from Vrtual Envoirnment
```
python manage.py createsuperuser
```

Run Migrations To Register local models.

```
python manage.py makemigrations
```

Run below command To Create database
```
python manage.py migrate
```

To run the Website run the follwing command
```
python manage.py runserver {port_number(optional)}
```
To access page visit http://localhost:{port_number}/admin



